这是一个关于本地web项目部署的docker-compose配置文件
你可以在以下网址上下载镜像到你电脑上
https://hub.docker.com/repository/docker/yang3498/web_docker-db-with-data
https://hub.docker.com/repository/docker/yang3498/web_docker-webapp
在此之后，你可以打开你镜像的安装目录，并打开命令控制符，输入：
docker-compose up
即可启动项目，在浏览器上输入：http://localhost:8080/adminIndex.jsp 打开管理员首页（账户：admin  密码：12345）。
输入：http://localhost:8080/userIndex.jsp    来到用户首页
输入：http://localhost:8080/doctorIndex.jsp   来到医生首页（账户：10001  密码：123456）
