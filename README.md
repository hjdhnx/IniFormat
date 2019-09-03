# IniFormat
一个基于原生JavaScript的ini解析器，最重要的是它支持换行。
```ini
[aaaa]
a=2132312
b=http://www.iwonmo.com
c=a
[b]
a=2132312

11
b=下一个节点是空节点
c=
[cc]
a=!%40%23%24%25%5e%26*()%7e_%2b%5b%5d%7b%7d%3d-%e6%82%a8%e5%a5%bd%ef%bc%8c%e8%bf%99%e6%98%af%e4%b8%80%e4%b8%aa%e6%b5%8b%e8%af%95%e6%96%87%e6%9c%ac%e3%80%82
newline
hello%ef%bc%8cthis+is+newline+text

[dd]




aaaa=222
```
![image](https://github.com/iwonmo/IniFormat/blob/master/readme.png)
