# Vim 编辑器（windows） 安装搭建自述文件

## 一、概述


### 1、 目的阐述

+  为搭建windows的Vim编辑器的依据与指导。

### 2、 读者对象

+  有意向使用Vim的读者；

### 3、 注意事项

+  该文档采用 markdown 编写规范，建议使用markdownPad查看和修改

## 二、安装步骤

#### 1、 目录结构

~~~

./          
├── _vimrc                                     用户自定义配置文件（内含有使用说明）
├── .vim.zip                                   插件包
├── ctags58.zip                                ctags的5.8版本的安装包
├── vimtweak.zip                               透明度窗口插件文件压缩包
├── gVim_7.4.zip                               gVim7.4基本安装包
├── gvim80_windows_20161023.exe                gVim8.0基本安装包
├── Markdown-Preview-Plus-Dz特别版_v104.crx    chrome核心的浏览器的Markdown阅读插件
├── Markdown-Preview-Plus_v0.6.5.crx           chrome核心的浏览器的Markdown阅读插件
└── README.md                                  自述文件（部署到生成环境后删除）

~~~


#### 2、 运行环境

+ Windows7及以上

#### 3、 安装步骤

+ a、先点击gvim80_windows_20161023.exe进行基本安装（或者解压gVim_7.4.zip安装7.4版本的）

+ b、进行配置 在当前账户的根目录下（如：win7 的 C:\Users\Administrator）下建立.vim 文件夹

+ c、将.vim.zip解压到 当前用户根目录下（ win7 的 C:\Users\Administrator ）

+ d、将vimtweak.zip解压到 将里面的vimtweak.dll 复制或移动到 vim的安装文件的vim.exe 同目录中 （ C:\Program Files (x86)\Vim\vim80 ）

+ e、将ctags58解压到 到某文件（如：C:\Software ） 将解压或的ctags58目录添加到系统环境的配置中

+ f、将_vimrc并复制到当前账户的根目录下（如：win7 的 C:\Users\Administrator）

## 三、参考资料

+ [在 Vim 中使用 Git 的插件: Fugitive](http://www.gnailuy.com/linux/2014/12/13/using-git-in-vim-with-fugitive/)

+ [vim比较目录diff](https://blog.csdn.net/littlewhite1989/article/details/45312081)

+ [nerdtree-git-plugin插件](https://github.com/Xuyuanp/nerdtree-git-plugin)

+ [每日vim插件--显示git diff:GitGutter.vim](http://ju.outofmemory.cn/entry/72482)