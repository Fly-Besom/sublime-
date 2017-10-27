# sublime汉化和安装插件教程

## 汉化

####1、sublime官网（http://www.sublimetext.com/）下载最新版本软件

#### 打开软件
###### 1.全局命令下，输入【ctrl+shift+p】，打开 Command Palette
######2.输入install找到：Package Control:Install回车，等待加载 package 列表

![41462e11d6721e41abac28e64bd19efb](.\img\41462e11d6721e41abac28e64bd19efb.png)

######安装插件中左下角有个“=”在动，安装好了就会消失
![ebfca1ac4efa144aa2cad5940d112837](.\img\ebfca1ac4efa144aa2cad5940d112837.png)
######3.Package Control:Install安装后就进入插件搜索了

![b1a3eb5bb7a26e4a8439bb817e8db9f1](.\img\b1a3eb5bb7a26e4a8439bb817e8db9f1.png)

######4.汉化插件：ChineseLocaization，安装好了选择帮助language选择中文简体就OK了



##安装插件
####1、注意事项：搜索插件之前都需要输入【ctrl+shift+p】在输入install找到：Package Control:Install回车，等待加载 package 列表，然后在搜索你要的插件进行安装。

## 推荐几款前端常用优秀插件

###1、emmet
####Emmet插件可以说是使用Sublime Text进行前端开发必不可少的插件，它让编写HTML代码变得极其简单高效

####![o_4-1](.\img\o_4-1.gif)

###2、JsFormat插件
####这是一款将JS格式化的插件，同样使用Package Control安装JsFormat插件后即可在JS文件中通过鼠标右键->JsFormat或键盘快捷键Ctrl+Alt+F对JS进格式化

![o_5-2](.\img\o_5-2.gif)

###3、SideBarEnhancements插件
####SideBarEnhancements是一款很实用的右键菜单增强插件，在安装该插件前，在Sublime Text左侧FOLDERS栏中点击右键只有寥寥几个简单的功能
####安装前![o_6-1](.\img\o_6-1.jpg)

####安装后![o_6-2](.\img\o_6-2.jpg)

###4、总之sublime插件很多，我就不一一列举了，你只需要点开百度（www.baidu.com） 搜索一下就行了，合适自己的才是最好的。



##推荐两款喜欢的主题(theme)
###Dracula Color Scheme(最喜欢的一种主题)
![20171027195537](.\img\20171027195537.png)

###Material Theme(这个是带侧边栏的)

![_20171027195931](.\img\_20171027195931.png)

###图标插件：A file Icon

![20171027200248](.\img\20171027200248.png)

####(注释：主题千千万，还是安装自己喜欢的吧！ 安装主题也是和安装插件的方法一样，安装好后选择首选项=>配色方案，然后自行选择)



##修改标签栏和侧边栏更改字体和大小方法

###安装插件PackageResourceViewer
####1、全局命令下，输入【ctrl+shift+p】，打开 Command Palette
####2、输入Package Control:Install回车，等待加载 package 列表
####3、搜索并安装 PackageResourceViewer 包

####安装完PackageResourceViewer后：
####输入【ctrl+shift+p】调出控制板，输入PackageResourceViewer: Open Resource这个命令
####进入到 XXX - Default 主题的目录下，打开对应的 XXX.sublime-theme 主题文件。（注：XXX为你主题的名字）
###更改相应的主题文件代码
####打开 XXX.sublime-theme 这个文件，如果你要更改侧边栏的大小，可以搜索sidebar_label关键词，在"class": "sidebar_label"后面增加下面的代码："font.size":13,(大小自己看着办)
```html
// Sidebar entry
{
    "class": "sidebar_label",
    "font.size": 13, //侧边栏字体大小
    "font.face": "Source_Code_Pro-雅黑 混合体", //侧边栏字体设置
},
```
####如果你要更改标签栏的字体和大小，同样是在这个文件里搜索tab_label关键词，在"class": "tab_label"后增加下面的代码："font.size": 13,(大小自己看着办)
```
// - Inactive tab label
{
    "class": "tab_label",
    "font.size": 13, //标签栏字体大小
    "font.face": "Source_Code_Pro-雅黑 混合体", //标签栏字体设置
},
```

#####(注释：基本安装就到这里，如果还有不懂的可以去百度)

