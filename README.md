About
---

uvsocks is a reliable socks client implemented using [libuv](https://github.com/libuv/libuv) for windows and linux.

It has support forward and reverse mode.

More information about socks5 : [RFC1928](http://www.ietf.org/rfc/rfc1928.txt "RFC1928")

Usage
---
   uvsocks [-L address:port]
           [-l login_name]
           [-a password]
           [-p port]
           [user:password@]hostname:port

Examples

`uvsocks -L 127.0.0.1:1234:192.168.0.231:8000 user:password@192.168.0.15:22`

`uvsocks -L 127.0.0.1:1234:192.168.0.231:8000 192.168.0.15 -l user -a password -p 22`

---


