# XDU-Beamer-Slide-V1

根据大连理工模板修改而来，**[源链接](https://github.com/fuujiro/DLUT-Beamer-Slide-V1)**

## 文档目录与编译方式

`TexLive 2020`完整编译方式为`xelatex -shell-escape XDU_BeamerTemplate`*2

或直接运行根目录下的`make.bat`

```bash
│  make.bat                                     #编译脚本
│  xdu.sty                                      #样式文件
│  XDU_BeamerTemplate.pdf                       #结果beamer
│  XDU_BeamerTemplate.tex                       #主文件
│  
├─figures                                       #图片文件
└─source                                        #模板用到的图片,不要删除
        xdu_background.png
        xdu_logo.png
        xdu_title.png
```
## minted宏包
本模板使用了minted宏包，因此需要配置Python环境并安装Pygments模块。
可以参照相应的文档或网上资料[latex中代码高亮显示宏包minted用法](https://blog.csdn.net/xenonhu/article/details/88978672)
