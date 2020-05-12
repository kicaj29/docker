# ls
# tar
# ps
# cd
# cat
Prints file content on the console.
# apk
Adds package.

Sample with adding jq package:
```
apk add --no-cache jq
```
# how to check linux version
docker run mcr.microsoft.com/dotnet/core/runtime 2.1.8
```
C:\Users\abc>docker run -it 860 bash
root@1be7d0d5dc66:/# cat /etc/*-release
PRETTY_NAME="Debian GNU/Linux 9 (stretch)"
NAME="Debian GNU/Linux"
VERSION_ID="9"
VERSION="9 (stretch)"
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
root@1be7d0d5dc66:/# time="2020-02-20T09:13:54+01:00" level=error msg="error waiting for container: EOF"
```
another example

docker run mcr.microsoft.com/dotnet/core/runtime 3.1-alpine
```
C:\WINDOWS\system32>docker run -it 3e11 sh
/ # cat /etc/*-release
3.11.3
NAME="Alpine Linux"
ID=alpine
VERSION_ID=3.11.3
PRETTY_NAME="Alpine Linux v3.11"
HOME_URL="https://alpinelinux.org/"
BUG_REPORT_URL="https://bugs.alpinelinux.org/"
```