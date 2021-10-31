
How to Install Oracle Java on Ubuntu Linux

https://www.guru99.com/how-to-install-java-on-ubuntu.htm


Download the last version of java in https://www.oracle.com/java/technologies/downloads/ make download of x64 Compressed Archive.

```
$ sudo su
# mkdir /opt/jdk
# tar -zxf jdk*.tar.gz -C /opt/jdk
# ls /opt/jdk
# update-alternatives --install /usr/bin/java java /opt/jdk/jdk*/bin/java 100
# update-alternatives --install /usr/bin/javac javac /opt/jdk/jdk*bin/javac 100
```
