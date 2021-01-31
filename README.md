[原仓库地址](https://github.com/OpenZeppelin/docs.openzeppelin.com)

项目基于[antora](https://docs.antora.org/antora/2.3/)框架构建。
不同于markdown，该文档框架采用ascii语法，详细用法参考[此处](https://docs.antora.org/antora/2.3/asciidoc/asciidoc/)

该开源项目已经内置了不同的开发脚本，详细功能请自行查看package.json,
我们主要需要关注以下三个部分

## 1.playbook.yml
项目的配置文件,包括指定文档的路径/主题文件的路径
## 2.components目录
存放编写好的文档以及控制文档的路由
## 3.ui目录
该目录自定义主题的源文件，负责页面的样式，依赖需要独立安装，，**运行bundle命令来生成主题文件oz-docs-ui.zip（这一步不可省略）**

菜单栏在header.hbs内修改

侧边栏在navigation.hbs内修改

页面js在footer-scripts.hbs内修改,建议只保留site.js以及highlight.js





