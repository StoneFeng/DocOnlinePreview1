如何使用这个demo ?
1.安装OpenOffice
2.进入{OpenOffice_Home}/program并使用如下命令行来启动OpenOffice服务
soffice -headless -accept="socket,host=127.0.0.1,port=8100;urp;" -nofirststartwizard
3.安装swftools并将其放到D:/SWFTools路径下
4.将该应用部署到tomcat容器中并启动tomcat
5.访问http://localhost:8080/DocOnlinePreview1