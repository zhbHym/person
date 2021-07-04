# github图片

图片访问路径为：

 git上传图片及文件方法：https://zhbhym.github.io/HexoImg + 文件路径
 
例如：https://zhbhym.github.io/HexoImg/scrapy/JetBrains01.png

1、关联远程路径，可以运行 

```
git clone https://github.com/zhbHym/HexoImg.git
```

2、本地中添加文件，如果有文件夹，则需要首先运行 
```
git add .
```
添加文件。

3、提交到本地仓库
``` bash
git commit -m "添加图片"
```
提交文件到本地仓库，-m后面为提交文件的注释

4、提交到远程仓库
```bash
git push origin master
```
提交文件到远程仓库的dev分支，如果只运行``git push``，则提交到默认分支master
