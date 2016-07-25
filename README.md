# Apache Ant Docker Image - Extends frekele/java

Repository: https://hub.docker.com/r/frekele/ant

#### Apache Ant with Oracle JDK Branches:
| Branch                      | From                     | Usage        | Tag Names                           |
| --------------------------- | ------------------------ | ------------ | ------------------------------------|
| [1.9.7-jdk8] - latest       | frekele/java:jdk8        | Production   | 1.9.7-jdk8, latest                  |
| [1.9.7-jdk8u102]            | frekele/java:jdk8u102    | Production   | 1.9.7-jdk8u102                      |
| [1.9.7-jdk8u101]            | frekele/java:jdk8u101    | Production   | 1.9.7-jdk8u101                      |
| [1.9.7-jdk8u92]             | frekele/java:jdk8u92     | Production   | 1.9.7-jdk8u92                       |
| [1.9.7-jdk8u91]             | frekele/java:jdk8u91     | Production   | 1.9.7-jdk8u91                       |
| [1.9.7-jdk8u77]             | frekele/java:jdk8u77     | Production   | 1.9.7-jdk8u77                       |
| [1.9.7-jdk8u74]             | frekele/java:jdk8u74     | Production   | 1.9.7-jdk8u74                       |
| [1.9.7-jdk8u73]             | frekele/java:jdk8u73     | Production   | 1.9.7-jdk8u73                       |
| [1.9.7-jdk8u72]             | frekele/java:jdk8u72     | Production   | 1.9.7-jdk8u72                       |
| [1.9.7-jdk8u71]             | frekele/java:jdk8u71     | Production   | 1.9.7-jdk8u71                       |
| [1.9.7-jdk8u66]             | frekele/java:jdk8u66     | Production   | 1.9.7-jdk8u66                       |
| [1.9.7-jdk8u65]             | frekele/java:jdk8u65     | Production   | 1.9.7-jdk8u65                       |
| [1.9.7-jdk8u60]             | frekele/java:jdk8u60     | Production   | 1.9.7-jdk8u60                       |
| [1.9.7-jdk8u51]             | frekele/java:jdk8u51     | Production   | 1.9.7-jdk8u51                       |
| [1.9.7-jdk7]                | frekele/java:jdk7        | Production   | 1.9.7-jdk7                          |
| [1.9.7-jdk7u80]             | frekele/java:jdk7u80     | Production   | 1.9.7-jdk7u80                       |
| [1.9.7-jdk7u79]             | frekele/java:jdk7u79     | Production   | 1.9.7-jdk7u79                       |
| [1.9.7-jdk7u76]             | frekele/java:jdk7u76     | Production   | 1.9.7-jdk7u76                       |
| [1.9.7-jdk7u75]             | frekele/java:jdk7u75     | Production   | 1.9.7-jdk7u75                       |
| [1.9.7-jdk7u72]             | frekele/java:jdk7u72     | Production   | 1.9.7-jdk7u72                       |
| [1.9.7-jdk7u71]             | frekele/java:jdk7u71     | Production   | 1.9.7-jdk7u71                       |
| [dev]                       | frekele/java:jdk8        | Development  | dev                                 |

# Dockerfile extends From:
- https://github.com/frekele/docker-java
- https://hub.docker.com/r/frekele/java


## Relations:
 - https://github.com/just-containers/s6-overlay

[1.9.7-jdk8]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8/Dockerfile
[1.9.7-jdk8u102]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u102/Dockerfile
[1.9.7-jdk8u101]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u101/Dockerfile
[1.9.7-jdk8u92]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u92/Dockerfile
[1.9.7-jdk8u91]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u91/Dockerfile
[1.9.7-jdk8u77]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u77/Dockerfile
[1.9.7-jdk8u74]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u74/Dockerfile
[1.9.7-jdk8u73]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u73/Dockerfile
[1.9.7-jdk8u72]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u72/Dockerfile
[1.9.7-jdk8u71]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u71/Dockerfile
[1.9.7-jdk8u66]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u66/Dockerfile
[1.9.7-jdk8u65]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u65/Dockerfile
[1.9.7-jdk8u60]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u60/Dockerfile
[1.9.7-jdk8u51]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk8u51/Dockerfile
[1.9.7-jdk7]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7/Dockerfile
[1.9.7-jdk7u80]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u80/Dockerfile
[1.9.7-jdk7u79]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u79/Dockerfile
[1.9.7-jdk7u76]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u76/Dockerfile
[1.9.7-jdk7u75]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u75/Dockerfile
[1.9.7-jdk7u72]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u72/Dockerfile
[1.9.7-jdk7u71]: https://github.com/frekele/docker-ant/blob/1.9.7-jdk7u71/Dockerfile
[dev]: https://github.com/frekele/docker-ant/blob/dev/Dockerfile
