本地 Web 项目部署的 Docker Compose 配置


此仓库包含一个用于部署本地 Web 项目的 Docker Compose 配置文件。您可以通过以下链接从 Docker Hub 下载所需的 Docker 镜像：



数据预加载的 MySQL 镜像

https://hub.docker.com/repository/docker/yang3498/web_docker-db-with-data 



应用镜像

https://hub.docker.com/repository/docker/yang3498/web_docker-webapp



如何运行项目



按照以下步骤在本地机器上设置并运行项目：



下载 Docker 镜像：



使用上面提供的 Docker 链接下载数据库和 Web 应用镜像。



进入项目目录：



下载完成后，进入保存 docker-compose.yml 文件的目录。

首先需要注意,当前mysql镜像还没有导入数据，我们需要先导入数据,具体操作如下：

打开命令行，输入以下命令以拉取镜像：

docker-compose up -d


docker ps










启动项目：


在项目目录中打开终端或命令提示符，并运行以下命令：

docker-compose up



访问 Web 应用：



容器启动并运行后，您可以通过 Web 浏览器访问应用程序的不同界面：



管理员首页：

Visit http://localhost:8080/adminIndex.jsp
Login credentials 登录凭据:
Username 用户名: admin
Password 密码: 12345

User Homepage 用户首页：

Visit http://localhost:8080/userIndex.jsp

Doctor Homepage 医生首页：

Visit http://localhost:8080/doctorIndex.jsp
Login credentials 登录凭据:

Username 用户名: 10001
Password 密码: 123456

Notes
注意事项


请确保 Docker 已正确安装并在您的计算机上运行。



如果您遇到任何问题或有任何疑问，请随时联系我或在此仓库中提交问题。
