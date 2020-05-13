# filesplit
split big file and collapse back

# install
```
npm i cutfile -g
```

# usage

```
//分割大文件到2M小文件
cutfile -f d:/aaa/bigfile.rar -d d:/aaa/part/ -s 2
```

```
//合并回来
cutfile -c -f d:/aaa/bingfileback.rar -d d:/aaa/part/
```

# Liecense
MIT LICENSE