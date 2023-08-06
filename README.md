# libstdc-so

libstdc++.so  some library for glibc


## usage

> deps on your os  && first copy lib to os

* centos 8

```code

rm -rf /lib64/libstdc++.so.6
ln -s /lib64/libstdc++.so.6.28 libstdc++.so.6
```

* centos 7

```code
rm -rf /lib64/libstdc++.so.6
ln -s /lib64/libstdc++.so.6.26 libstdc++.so.6
```

* ubuntu 16 | 18 

```code
rm -rf /usr/lib/x86_64-linux-gnu/libstdc++.so.6
ln -s  /usr/lib/x86_64-linux-gnu/libstdc++.so.6.0.26  /usr/lib/x86_64-linux-gnu/libstdc++.so.6
```# libstdc-so

libstdc++.so  some library for glibc
