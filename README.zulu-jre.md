## Tags
+ `docker pull mcr.microsoft.com/java/jre`
        
Java 8 Update 181:
+ `8u181-zulu-alpine` - [Dockerfile][zulu8-jre-alpine]
+ `8u181-zulu-centos` - [Dockerfile][zulu8-jre-centos]
+ `8u181-zulu-debian8` - [Dockerfile][zulu8-jre-debian8]
+ `8u181-zulu-debian9` - [Dockerfile][zulu8-jre-debian9]
+ `8u181-zulu-ubuntu` - [Dockerfile][zulu8-jre-ubuntu]
+ `8u181-zulu-windowsservercore` - [Dockerfile][zulu8-jre-windowsservercore]

Java 7 Update 191:
+ `7u191-zulu-alpine` - [Dockerfile][zulu7-jre-alpine]
+ `7u191-zulu-centos` - [Dockerfile][zulu7-jre-centos]
+ `7u191-zulu-debian8` - [Dockerfile][zulu7-jre-debian8]
+ `7u191-zulu-debian9` - [Dockerfile][zulu7-jre-debian9]
+ `7u191-zulu-ubuntu` - [Dockerfile][zulu7-jre-ubuntu]
+ `7u191-zulu-windowsservercore` - [Dockerfile][zulu7-jre-windowsservercore]

[zulu8-jre-alpine]:https://github.com/Microsoft/java/tree/master/docker/alpine/Dockerfile.zulu-8u181-jre
[zulu8-jre-centos]:https://github.com/Microsoft/java/tree/master/docker/centos/Dockerfile.zulu-8u181-jre
[zulu8-jre-debian8]:https://github.com/Microsoft/java/tree/master/docker/debian8/Dockerfile.zulu-8u181-jre
[zulu8-jre-debian9]:https://github.com/Microsoft/java/tree/master/docker/debian9/Dockerfile.zulu-8u181-jre
[zulu8-jre-ubuntu]:https://github.com/Microsoft/java/tree/master/docker/ubuntu/Dockerfile.zulu-8u181-jre
[zulu8-jre-windowsservercore]:https://github.com/Microsoft/java/tree/master/docker/windowsservercore/Dockerfile.zulu-8u181-jre

[zulu7-jre-alpine]:https://github.com/Microsoft/java/tree/master/docker/alpine/Dockerfile.zulu-7u191-jre
[zulu7-jre-centos]:https://github.com/Microsoft/java/tree/master/docker/centos/Dockerfile.zulu-7u191-jre
[zulu7-jre-debian8]:https://github.com/Microsoft/java/tree/master/docker/debian8/Dockerfile.zulu-7u191-jre
[zulu7-jre-debian9]:https://github.com/Microsoft/java/tree/master/docker/debian9/Dockerfile.zulu-7u191-jre
[zulu7-jre-ubuntu]:https://github.com/Microsoft/java/tree/master/docker/ubuntu/Dockerfile.zulu-7u191-jre
[zulu7-jre-windowsservercore]:https://github.com/Microsoft/java/tree/master/docker/windowsservercore/Dockerfile.zulu-7u191-jre

## About
	These Zulu OpenJDK Docker images and corresponding Dockerfiles are
	to be used solely with Java applications or Java application components
	that are being developed for deployment on Microsoft Azure or Azure Stack,
	and are not intended to be used for any other purpose.

	Each image contains the base operating system, taken at a point in time,
	and an installed version of the Azul Zulu Full JRE (Java Runtime Environment).

## How To Use
+ `docker pull mcr.microsoft.com/java/jre:tag`
+ `docker run --rm -it mcr.microsoft.com/java/jre:tag`

## Featured Repositories
* `https://repos.azul.com/azure-only/zulu/yum`
* `https://repos.azul.com/azure-only/zulu/apt`

## Quick Reference
* [Azul Zulu JVM for Azure FAQ](https://assets.azul.com/files/Zulu-for-Azure-FAQ.pdf)
* [Azul Zulu JVM for Azure](https://www.azul.com/downloads/azure-only/zulu/)

## License
[Zulu for Microsoft Azure Terms of Use](https://www.azul.com/downloads/azure-only/zulu/terms-of-use)

## Support
[Microsoft Azure Support](https://support.microsoft.com/en-us/help/4026305/sql-contact-microsoft-azure-support)

## Issues
Report Docker image or Dockerfile issues [here](https://github.com/Microsoft/java/issues)

## Further Reading
* [Java on Azure](https://azure.microsoft.com/en-us/develop/java/)
* [Azure for Java Developers](https://docs.microsoft.com/en-us/java/azure/?view=azure-java-stable)
* [Azul](https://www.azul.com/)
* [Azul Zulu Enterprise](https://www.azul.com/products/zulu-enterprise/)
* [Azul Zulu Embedded](https://www.azul.com/products/zulu-embedded/)

