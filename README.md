# acmetest
Unit test project for le project https://github.com/Neilpang/acme.sh



# Here are the latest status:

| Platform | Status| Last Run Time| Comments|
-----------|-------|--------------|---------|
|windows-cygwin| ![](https://cdn.rawgit.com/Neilpang/acmetest/master/status/windows-cygwin.svg?1461388681)| Sat, Apr 23, 2016  5:18:01 AM| Passed |
|freebsd| ![](https://cdn.rawgit.com/Neilpang/acmetest/master/status/freebsd.svg?1461381345)| Sat Apr 23 03:15:45 UTC 2016| Passed |
|openbsd| ![](https://cdn.rawgit.com/Neilpang/acmetest/master/status/openbsd.svg?1461477451)| Sun Apr 24 05:57:31 UTC 2016| Passed |
|ubuntu:14.04| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-14.04.svg?1461496545)| Sun Apr 24 11:15:45 UTC 2016| Passed |
|ubuntu:15.04| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-15.04.svg?1461496934)| Sun Apr 24 11:22:14 UTC 2016| Passed |
|ubuntu:16.04| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-16.04.svg?1461497394)| Sun Apr 24 11:29:54 UTC 2016| Passed |
|ubuntu:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-latest.svg?1461497757)| Sun Apr 24 11:35:57 UTC 2016| Passed |
|debian:7| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-7.svg?1461498119)| Sun Apr 24 11:41:59 UTC 2016| Passed |
|debian:8| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-8.svg?1461498493)| Sun Apr 24 11:48:13 UTC 2016| Passed |
|debian:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-latest.svg?1461498860)| Sun Apr 24 11:54:20 UTC 2016| Passed |
|centos:5| ![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-5.svg?1461499166)| Sun Apr 24 11:59:26 UTC 2016| Failed |
|centos:6| ![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-6.svg?1461499947)| Sun Apr 24 12:12:27 UTC 2016| Failed |
|centos:7| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-7.svg?1461500365)| Sun Apr 24 12:19:25 UTC 2016| Passed |
|centos:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-latest.svg?1461500774)| Sun Apr 24 12:26:14 UTC 2016| Passed |
|fedora:21| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-21.svg?1461501171)| Sun Apr 24 12:32:51 UTC 2016| Passed |
|fedora:22| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-22.svg?1461501569)| Sun Apr 24 12:39:29 UTC 2016| Passed |
|fedora:23| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-23.svg?1461501962)| Sun Apr 24 12:46:02 UTC 2016| Passed |
|fedora:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-latest.svg?1461502370)| Sun Apr 24 12:52:50 UTC 2016| Passed |
|opensuse:13.2| ![](https://cdn.rawgit.com/Neilpang/letest/master/status/opensuse-13.2.svg?1461503074)| Sun Apr 24 13:04:34 UTC 2016| Failed |
|opensuse:42.1| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/opensuse-42.1.svg?1461503426)| Sun Apr 24 13:10:26 UTC 2016| Passed |
|opensuse:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/opensuse-latest.svg?1461503802)| Sun Apr 24 13:16:42 UTC 2016| Passed |
|alpine:3.1| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/alpine-3.1.svg?1461504110)| Sun Apr 24 13:21:50 UTC 2016| Passed |
|alpine:3.2| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/alpine-3.2.svg?1461504402)| Sun Apr 24 13:26:42 UTC 2016| Passed |
|alpine:3.3| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/alpine-3.3.svg?1461504690)| Sun Apr 24 13:31:30 UTC 2016| Passed |
|alpine:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/alpine-latest.svg?1461504990)| Sun Apr 24 13:36:30 UTC 2016| Passed |
|oraclelinux:6| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/oraclelinux-6.svg?1461505397)| Sun Apr 24 13:43:17 UTC 2016| Passed |
|oraclelinux:7| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/oraclelinux-7.svg?1461505821)| Sun Apr 24 13:50:21 UTC 2016| Passed |
|oraclelinux:latest| \![](https://cdn.rawgit.com/Neilpang/letest/master/status/oraclelinux-latest.svg?1461506213)| Sun Apr 24 13:56:53 UTC 2016| Passed |
|kalilinux/kali-linux-docker| ![](https://cdn.rawgit.com/Neilpang/letest/master/status/kalilinux-kali-linux-docker.svg?1461506945)| Sun Apr 24 14:09:05 UTC 2016| Passed |
(The openssl in CentOS 5 doesn't support ECDSA, so the ECDSA test cases failed. However, RSA certificates are working there.)

# How to run tests

First point at least 2 of your domains to your machine, 
for example: `aa.com` and `www.aa.com`

And make sure 80 port is not used by anyone else.

```
cd letest
TestingDomain=aa.com   TestingAltDomains=www.aa.com  ./letest.sh
```

# How to run tests in all the platforms through docker.

You must have docker installed, and also point 2 of your domains to your machine.

Then test all the platforms :

```
cd letest
TestingDomain=aa.com   TestingAltDomains=www.aa.com  ./rundocker.sh  testall
```

The script will download all the supported platforms from the official docker hub, then run the test cases in all the supported platforms.






