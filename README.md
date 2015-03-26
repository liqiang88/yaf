# windows php_yaf扩展
适用于windows，php5.4.x
非线程安全用php_yaf-2.2.8-x86-5.4.x-nts-nodebug.dll
线程安全用php_yaf-2.2.8-x86-5.4.x-zts-nodebug.dll
将php_yaf.xx.dll放到php的扩展目录，php.ini文件添加extentsion=php_yaf.xx.dll
(xx是php_yaf dll文件的全名)
重启web服务器。
查看phpinfo()中是否yaf？ 有即成功。
