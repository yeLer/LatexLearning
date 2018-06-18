我们从ArXiv下载到的内容文件如当前的文件夹下的内容所示：
acmart.cls文件是latex2e的格式文件，它决定了latex源文件的排版布局。最一般的cls文件就是我们常用的article.cls,这表现在 
\documentclass{article} 
这一句里面。如果出版方提供了cls文件，假如cls文件名为xxx.cls： 
cls文件和你自己的latex文件放到同一个文件夹里面，在源文件里面用 \documentclass{xxx} 
而不是 \documentclass{article} 

figfile2.eps是图片格式的文件，用于在tex文件中调用显示

samplebody-conf.tex是主要内容的tex文件，它可以只是包含主要部分的内容，可以在主入口文件中提供调用显示，这样就可以实现内容
之间分离、内容与格式分离。

sample-sigconf-authordraft.bbl是提供参考文献功能的文件

sample-sigconf-authordraft.tex是tex的主文件，这里是可运行的文件。

sample-sigconf-authordraft.pdf是运行sample-sigconf-authordraft.tex生成的文件。
