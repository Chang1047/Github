# 选择外网延迟小的网址

国内运行github真的超级超级慢，有时候甚至加载不出来



## 输入网址选择TTL最小的值

```ABAP
http://tool.chinaz.com/dns/?type=1&host=github.com&ip=
```



# 更改hosts的文件

文件所在的位置

```ABAP
C:\Windows\System32\drivers\etc
```

添加刚才复制的网址 后面跟github.com

例如：13.114.40.48  github.com



## 若文件无法修改

把文件达到桌面用txt打开，修改完成后，再放回原来的位置



# 测试

github.com    明显直接打开，再也不用担心网慢了

