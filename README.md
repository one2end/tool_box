# 个人工具箱

个人日常处理文件较多，老是自己写代码。现在想把常用的功能合并写一个模块方便使用和调用。按照日常使用情况，工具箱分别的两种对象进行操作。

## 文件夹

针对文件夹对象，主要有一下几个方法。

1. 文件搜索。扫描文件夹内所有文件，返回文件夹内所有子文件或指定后缀文件列表。

1. 文件分类。对所有文件进行分类并对同类文件创建以后缀结尾的子文件夹归类。如果里面本来就有子文件夹，增加参数选择遍历所有文件夹、遍历几级文件夹或者选择忽略子文件夹。

1. 文件合并。对文件列表执行合并。计划支持格式（xls，xlsx，csv，doc，txt，md，pdf）。文本文件按照追加形式合并，表格按照工作表位置合并为一个工作簿。

1. 文件压缩。使用固定密码对文件进行压缩。

1. 批量重命名。针对文件夹内子文件或者文件进行批量重命名。增加前缀、后缀。删除指定内容，忽略文件后缀名称。

## 文件

针对特定文件格式进行处理。

1. zip、rar格式文件，可以使用解压缩方法。解压缩到文件当前目录并返回文件夹地址。

1. doc、xls、ppt文件转换为docx、xlsx、pptx。

1. docx、xlsx、pptx文件转换为html。

1. 