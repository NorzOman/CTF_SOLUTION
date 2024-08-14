
When we click on the link we are greeted with this screen

![[Pasted image 20240814181034.png]]

Since its related to robots we append /robots.txt to check for any flags

We find something interesting:

```
User-agent: *
Disallow: /1bb4c.html
```

Then we append the /lbb4c.html to our url and access the page

Then we get this:

![[Pasted image 20240814181158.png]]


So we found the flag:

```
picoCTF{ca1cu1at1ng_Mach1n3s_1bb4c}
```


