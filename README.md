<!-- title: 【ReadME】node-bootstrap文档 -->
<!-- subtitle: 20140810 -->
## node-bootstrap的使用

目的：根据MARKDOWN文件自动生成html文档

修改自npm install markdown2bootstrap模块

运行环境：node环境（自行安装）

## 安装

    $ git clone http://git.mingchao.com/git/linkailian/md2bootstrap.git

进入项目目录.

将.md文件复制到项目目录

执行

    $ node_modules/.bin/markdown2bootstrap doc.md

win

    node_modules\.bin\markdown2bootstrap doc.md

就可以创建bootstrap模板的html文件

## **批量转换**.md文件

    $ node_modules/.bin/markdown2bootstrap doc1.md doc2.md ...
    Converted doc1.md to doc1.html
    Converted doc2.md to doc2.html
    ...

## 转换为没有数字序号html文件

    $ node_modules/.bin/markdown2bootstrap -n doc.md

## 如何修改**标题**

在md文件中修改对应**注释**

        <!-- title: This is a title -->
        <!-- subtitle: This is a subtitle -->

## 将文件输出到**指定目录**，默认后缀`.html`

    $ node_modules/.bin/markdown2bootstrap --outputdir html doc.md
    Converted  doc.md to html/doc.html

## markdow写作示例

参考README.md，更多[Markdown 语法说明](http://wowubuntu.com/markdown/#p)

## 效果

![demo](/images/demo.png)

    