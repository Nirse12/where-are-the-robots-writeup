# where-are-the-robots-writeup

## PicoCTF, Web Explotation

### AUTHOR: ZARATEC/DANNY

> Description
> Can you find the robots? https://jupiter.challenges.picoctf.org/problem/60915/ (link) or http://jupiter.challenges.picoctf.org:60915

This one was pretty easy, the description gave it up.

looking at the url : 

![image](https://user-images.githubusercontent.com/71516380/142755532-66a29769-b2ee-425b-a580-8eafcb9e4cd6.png)

since description mentioned robots.txt (a method used by google to index websites), i jumped into /robots.txt and got this:
```
User-agent: *
Disallow: /8028f.html
```

So, I went into that url and thats it.

FLAG : 
```
picoCTF{ca1cu1at1ng_Mach1n3s_8028f}
```

