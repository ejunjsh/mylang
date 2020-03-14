# mylang

my programming language pratice

## interpreter

from [基于c语言自制编程语言](https://book.douban.com/subject/30311070/)

## compiler

from https://github.com/DoctorWkt/acwj

### get started

i use docker as my environment, so you need to install docker desktop first if you are not in linux

then

    docker run -it -v $(pwd):/opt/tmp/ --rm -w /opt/tmp gcc make test