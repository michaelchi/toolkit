#### search
```
grep -rn '' . | grep -iv '\.svn' | grep --color=auto -i ''
```

```
--color=auto 显示颜色
-c : 计算找到'搜索字符串'的次数
-i : 忽略大小写
-v : 反向查找，即显示没有'搜索字符串'内容的那行
-o : 只显示被模式匹配的字符串
-n : 输出行号
-A : 显示匹配到字符那行的后面n行
-B : 显示匹配到字符那行的前面n行
-C : 显示匹配到字符那行的前后n行
```