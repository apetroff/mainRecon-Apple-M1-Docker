# mainRecon-Apple-M1-Docker
Fixed Dockerfile to run on Apple M1 

This repo contains fixed and updated Dockerfile of https://github.com/l34r00t/mainRecon to be run on Apple Macbook with M1.

What's Changed:
==

* Fixed the following on `docker build -t mainrecon .`:
```
#13 14.20 qemu-x86_64: Could not open '/lib64/ld-linux-x86-64.so.2': No such file or directory
```
* updated bumped up version of `go` and `findomain`.
* changed `aquatone` to [@shelld3v](https://github.com/shelld3v)'s [version](https://github.com/shelld3v/aquatone)
* updated `go get` to `go install`
