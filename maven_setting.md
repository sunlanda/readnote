## maven_idea_配置 ##


###配置前下载项:
>1.java 下载并安装 

>2.apacheTomcat 

>3.maven 下载后解压

>4.B2B项目官网setting.xml文件

###各个内容充当的角色
* maven 包管理工具 从服务器上下载依赖项
* tomcat 启动服务 联通环境 
* idea IDE代码编辑器 作为调试工具和搭载平台用

###idea操作

>1.setting->build->maven ->userSetting ->files ->上传setting.xml文件

>2.java版本选择6.0 jre版本

>3.端口一般80 如果有host 则打开switchHost进行配置

>4.maven一般配置完后需要fix exploded一下 会自动找到索引文件

###备注
一般setting.xml文件都放在maven/conf/路径下


