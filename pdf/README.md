# 环境

- python 3.8.5
- PyPDF2 1.260
- pdfplumber 0.5.28
- pdf2image 1.15.1

# PDF分割：splitPDF.py

使用方法：在cmd中输入：

> python splitPDF.py --pdf_path F:\pythonProject\data\GNN.pdf --save_directory F:\pythonProject\data --step 4

- --pdf_path：是pdf文件的绝对路径
- --save_directory：是pdf文件分割后的文件存储绝对路径
- --step：是按多少页分割成一个文件



# PDF合并：mergePDF.py

使用方法：在cmd中输入：

> python mergePDF.py --filename GNN --read_dirpath F:\pythonProject\data --save_dirpath F:\pythonProject\result

- --filename：文件名
- --read_dirpath：要合并的 PDF 目录
- --save_dirpath：合并后的 PDF 文件路径



# PDF转化为图片

使用方法：在cmd中输入：

> python pdfToImage.py --pdf_path F:\pythonProject\data\GNN1.
> pdf --pic_dirpath F:\pythonProject\result

- --pdf_path：要转化为图片的pdf的绝对路径
- --pic_dirpath：用于存放图片的文件夹路径

# 参考

组队学习：https://github.com/datawhalechina/team-learning-program/tree/master/OfficeAutomation