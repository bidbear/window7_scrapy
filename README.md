# window7_scrapy
 

1. 首先下载scrapy的whl包：http://www.lfd.uci.edu/~gohlke/pythonlibs/

下载Scrapy‑1.3.3‑py2.py3‑none‑any.whl

 

2. 没有安装过wheel库的请先安装pip install wheel

 

3. scrapy依赖twiste，进入http://www.lfd.uci.edu/~gohlke/pythonlibs/，找到适合的版本，

下载Twisted‑17.1.0‑cp36‑cp36m‑win_amd64.whl

 

4. scrapy依赖lxml包，pip install lxml

 

5. 在下载存放的目录下安装pip install Twisted-17.1.0-cp36-cp36m-win_amd64.whl 

 

6. 在下载存放的目录下安装pip install Scrapy-1.3.3-py2.py3-none-any.whl

 

7. 验证，输入scrapy -h，显示版本号，即成功！

输入scrapy shell url（网址）               
如果提示no modul pywin32              
需要执行第八步
8. scrapy依赖pywin32包

 下载pywin32的whl包：https://www.lfd.uci.edu/~gohlke/pythonlibs/ 
 
 pip install xxxx.whl
