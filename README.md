## Java with CentOS 7

This is docker images of CentOS 7 with different versions of java

[![Docker Stars](https://img.shields.io/docker/stars/chenmins/java-centos.svg)]() [![Docker Pulls](https://img.shields.io/docker/pulls/chenmins/java-centos.svg)]() [![Docker Automated buil](https://img.shields.io/docker/automated/chenmins/java-centos.svg)]() [![Docker Build Statu](https://img.shields.io/docker/build/chenmins/java-centos.svg)]()

[![](https://images.microbadger.com/badges/image/chenmins/java-centos.svg)](https://microbadger.com/images/chenmins/java-centos "Get your own image badge on microbadger.com") [![](https://images.microbadger.com/badges/version/chenmins/java-centos.svg)](https://microbadger.com/images/chenmins/java-centos "Get your own version badge on microbadger.com") [![](https://images.microbadger.com/badges/license/chenmins/java-centos.svg)](https://microbadger.com/images/chenmins/java-centos "Get your own license badge on microbadger.com")

[![GitHub forks](https://img.shields.io/github/forks/chenmins/java-centos.svg?style=social&label=Fork)]() [![GitHub stars](https://img.shields.io/github/stars/chenmins/java-centos.svg?style=social&label=Star)]() [![GitHub watchers](https://img.shields.io/github/watchers/chenmins/java-centos.svg?style=social&label=Watch)]() [![GitHub followers](https://img.shields.io/github/followers/chenmins.svg?style=social&label=Follow)]()

### Loading different versions of java

The different version is determined with the TAG 

The available version are 

* latest                 - currently Oracle Java version 8 JRE
* openjdk-7-jdk          - OpenJDK Java version 7 JDK
* openjdk-7-jre          - OpenJDK Java version 7 JRE
* openjdk-7-jre-headless - OpenJDK Java version 7 JRE headless
* openjdk-8-jdk          - OpenJDK Java version 8 JDK
* openjdk-8-jre          - OpenJDK Java version 8 JRE
* openjdk-8-jre-headless - OpenJDK Java version 8 JRE headless
* oracle-7-jre           - Oracle Java version 7 JRE
* oracle-7-jdk           - Oracle Java version 7 JDK
* oracle-8-jre           - Oracle Java version 8 JRE
* oracle-8-jdk           - Oracle Java version 8 JDK

Example to run a container with OpenJDK version 7 JDK

`docker run -ti --rm chenmins/java-centos:openjdk-7-jdk`

```bash
docker run -it --rm chenmins/java-centos /bin/bash
[root@40844ba27eae ~]# java -version
java version "1.8.0_121"
Java(TM) SE Runtime Environment (build 1.8.0_121-b13)
Java HotSpot(TM) 64-Bit Server VM (build 25.121-b13, mixed mode)
```



