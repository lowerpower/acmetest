# letest
Unit test project for le project https://github.com/Neilpang/le



# Here are the latest status:

| Platform | Status| Last Run Time| Comments|
-----------|-------|--------------|---------|
|ubuntu:14.04|![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-14.04.svg)|Wed Mar 16 16:17:17 UTC 2016| Passed |
|ubuntu:15.04|![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-15.04.svg)|Wed Mar 16 16:18:23 UTC 2016| Passed |
|ubuntu:latest|![](https://cdn.rawgit.com/Neilpang/letest/master/status/ubuntu-latest.svg)|Wed Mar 16 16:19:25 UTC 2016| Passed |
|debian:7|![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-7.svg)|Wed Mar 16 16:20:30 UTC 2016| Passed |
|debian:8|![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-8.svg)|Wed Mar 16 16:21:32 UTC 2016| Passed |
|debian:latest|![](https://cdn.rawgit.com/Neilpang/letest/master/status/debian-latest.svg)|Wed Mar 16 16:22:34 UTC 2016| Passed |
|centos:5|![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-5.svg)|Wed Mar 16 16:23:17 UTC 2016| Failed |
|centos:6|![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-6.svg)|Wed Mar 16 16:24:22 UTC 2016| Passed |
|centos:7|![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-7.svg)|Wed Mar 16 16:25:30 UTC 2016| Passed |
|centos:latest|![](https://cdn.rawgit.com/Neilpang/letest/master/status/centos-latest.svg)|Wed Mar 16 16:26:37 UTC 2016| Passed |
|fedora:21|![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-21.svg)|Wed Mar 16 16:27:45 UTC 2016| Passed |
|fedora:22|![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-22.svg)|Wed Mar 16 16:28:54 UTC 2016| Passed |
|fedora:23|![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-23.svg)|Wed Mar 16 16:30:02 UTC 2016| Passed |
|fedora:latest|![](https://cdn.rawgit.com/Neilpang/letest/master/status/fedora-latest.svg)|Wed Mar 16 16:31:11 UTC 2016| Passed |
|opensuse:13.2|![](https://cdn.rawgit.com/Neilpang/letest/master/status/opensuse-13.2.svg)|Wed Mar 16 16:32:18 UTC 2016| Passed |
|opensuse:42.1|![](https://cdn.rawgit.com/Neilpang/letest/master/status/opensuse-42.1.svg)|Wed Mar 16 16:33:23 UTC 2016| Passed |
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






