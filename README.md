hugo_0.72.0_Windows-64bit

Hugo模板

```
https://themes.gohugo.io/roxo-hugo/
```

如何使用：

```
1.下载
2.hugo new site aftree   # aftree 是一个目录，下面自动生成一堆文件
3.themes 目录下放入下载的模板， themes\roxo\模板文件
4.模板下面，exampleSite的内容，覆盖到aftree目录下
```

本地启动

```bash
hugo server -D
```

生成到docs目录

```bash
hugo  --baseUrl="https://aftree.cc/" -d docs
```

roxo模板，可以修改