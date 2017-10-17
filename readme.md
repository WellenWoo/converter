# **intergate_converter**(集成转换器)

0. 本软件是一个集成的格式转换器，可实现各文档格式间的转换。
1. converter由三个模块组成：files2pdf,imgs2pdf,docx2html。
2. files2pdf模块：将多个指定的文档打包到一个pdf文件中。
选择需要进行转换格式的文件夹，在"file's type"框填入需要进行
转换的文件格式（现支持.txt文档和.html文档），在"output pdfname"框填入输出的pdf文件名，点击run:files2pdf按钮即可完成转换。
将网页转为pdf文档，在"url"框中填入网页链接，"output pdfname"
框中填入输出的pdf文件名，点击run:url2pdf按钮即可完成转换。
将批量网页链接打包一个pdf文件中，选择含有多个网页链接的txt文档或
json文档，在"output pdfname"框填入输出的pdf文件名，
点击run:links2pdf按钮即可完成转换。
3. imgs2pdf模块：将多张图片打包到一个pdf文档中。
选择需要进行转换格式的文件夹，在"file's type"框
填入需要进行转换的文件格式（现仅支持.jpg/.jpeg格式的图片），
在"pdfname"框填入输出的pdf文件名，点击run按钮即可完成转换。
4. docx2html模块：将docx文档转换为html文档。
选择需要进行转换的docx文档，在"output name"框填入输出
的pdf文件名，点击run按钮即可完成单个文档的转换。
将批量的docx文档转换为.html文档，选择需要进行转换格式的文件夹，
指定文档输出的目标文件夹（若不指定则默认为原文件夹），
若目标文件夹中有同名文档，将不会覆盖原文档，点击run_bat按钮即可完成转换。


## Todo:
增加对多种图片格式的支持。

## Feedback:
有任何疑问或建议欢迎[反馈](https://github.com/WellenWoo/converter)。



