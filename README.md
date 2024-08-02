```bas
Usage: mux [port] [port] [key]
   or: mux [ip] [port] [name]

Eg:
server:
$ mux 1234 2345 key
[0]$

client:
mux 127.0.0.1 1234 ttt
$

and server:
mux 1234 2345 key
[0]$ /
#0 ttt R0 [2024-08-02 10:40:10.410 7]
[0]$

```

