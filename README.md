[10]: https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=289011
[11]: https://bugs.freebsd.org/bugzilla/show_bug.cgi?id=289635

# superhtml.port

A FreeBSD port.
I'm jumping the gun and moving to zig 0.15.1 early. Have to for this.

The following bugs already track some of this:
  - [289011][10]
  - [289635][11]

They also have the patches you need to move to zig 0.15.1 if you want to try superhtml.

If you have applied and build zig with patches:
```
# cd /usr/ports/devel
# git clone git@github.com:dmarker/superhtml.port.git superhtml
# cd superhtml
# make install clean
```

I had to use a branch of zig2tuple to make this port, delightful utility.
You don't need it to build or use superhtml. But if you want to port more
zig tools you will want it.
