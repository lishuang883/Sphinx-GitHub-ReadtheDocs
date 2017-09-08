.. Python documentation master file, created by
   sphinx-quickstart on Fri Sep 01 14:27:39 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

如何用Sphinx 、GitHub 、ReadtheDocs、搭建写书环境
=================================================
用 Sphinx 生成文档，GitHub 托管文档，再导入到 ReadtheDocs。

Sphinx 是一个基于 Python 的文档生成工具，最早只是用来生成 Python 官方文档，随着工具的完善，越来越多的知名的项目也用他来生成文档，甚至完全可以用他来写书

引用几点 Sphinx 的优势：
 * 丰富的输出格式: 支持 HTML (包括 Windows 帮助文档), LaTeX (可以打印PDF版本), manual pages（man 文档）, 纯文本 
 * 完备的交叉引用: 语义化的标签,并可以自动化链接函数,类,引文,术语及相似的片段信息 
 * 明晰的分层结构: 可以轻松的定义文档树,并自动化链接同级/父级/下级文章 
 * 美观的自动索引: 可自动生成美观的模块索引 
 * 精确的语法高亮: 基于 Pygments 自动生成语法高亮
https://zh-sphinx-doc.readthedocs.io/en/latest/contents.html

参考文档：（由于没有接触过，所以当时搭建的我很懵逼，只是参考了一下的文章，各个文章里都是缺少细节，但是都互相补缺，还冗杂，所以整理一下步骤，供哥哥姐姐们方便阅读，也有可能冗杂，所以见谅）
1. http://www.cnblogs.com/yanhuiw/p/3756085.html
2. http://blog.csdn.net/weishantc/article/details/45480917
3. http://blog.csdn.net/weishantc/article/details/46729103
4 http://yidao620c.github.io/2017/01/22/fullstack/readthedoc.html
5. http://www.jianshu.com/p/78e9e1b8553a
6.https://www.ibm.com/developerworks/cn/opensource/os-sphinx-documentation/

Contents:

.. toctree::
   :maxdepth: 2
	
   list1
   list2
   list3




* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
