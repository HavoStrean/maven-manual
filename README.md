# maven-manual
Maven使用手册,很早之前的文章，现在记录到github。
# Maven使用手册
 1.  Maven...它是什么？
--------------------------------------------------
>正式的  Apache Maven  的定义：  Maven 是一个项目管理工具，它包含了一个项目对象模型  (Project Object Model)，一组标准集合，一个项目生命周期(Project Lifecycle)，一个依赖管理系统(Dependency Management System)，和用来运行定义在生命周期阶段(phase)中插件(plugin)目标(goal)的逻辑。  当你使用 Maven 的时候，你用一个明确定义的项目对象模型来描述你的项目，然后  Maven  可以应用横切的逻辑，这些逻辑来自一组共享的（或者自定义的）插件。
2. 安装与运行Maven
--------------------------------------------------
### 2.1 验证你的 Java 安装
尽管 Maven 可以运行在 Java 1.4 上，但本书假设你在至少 Java 5 上运行。尽管使用你操作系统上最新的稳定版本的 JDK。**项目开发中，使用Java 6来开发**。  

    java -version   
    C:\Users\2B>java -version  
    java version "1.6.0_34"  
    Java(TM) SE Runtime Environment (build 1.6.0_34-b04)  
    Java HotSpot(TM) 64-Bit Server VM (build 20.9-b04, mixed mode)  
### 2.2 下载Maven
你可以从 Apache Maven 项目的 web 站点下载 Maven：
http://maven.apache.org/download.html.   
当你下载 Maven 的时候，确认你选择了最新版本的 Apache Maven。该文档写的时
候最新版本是 Maven 3.1.1  。
### 2.3 安装 Maven 
2.3.1 在 Windows 上安装 Maven  
在 Windows 上安装 Maven 最主要的是 **安装位置** 和 **设置环境变量**。在这里假设Maven安装目录是F:\Work_Tools\springsource\apache-maven-3.0.3，但是，只要你设置的正确的环境变量，把 Maven 安装到其它
目录也一样。当你把 Maven 解压到安装目录后，你需要设置两个环境变量——PATH
和 MAVEN_HOME。  
在控制面板中修改环境变量
### 2.4 验证Maven安装  
    C:\Users\2B>mvn -v  
    Apache Maven 3.0.3 (r1075438; 2011-03-01 01:31:09+0800)  
    Maven home: F:\springsource\apache-maven-3.0.3\bin\..  
    Java version: 1.6.0_34, vendor: Sun Microsystems Inc.  
    Java home: C:\Program Files\Java\jdk1.6.0_34\jre  
    Default locale: zh_CN, platform encoding: GBK    
    OS name: "windows 7", version: "6.1", arch: "amd64", family: "windows"  
