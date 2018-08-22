# Notes
jvm

java 中 main函数是栈的起始点，也是程序的入口

堆是线程间共享的存储区域；



totalMemory其值相当于当前JVM已使用的内存及freeMemory()的总和 

设置JVM运行参数的方法

在命令行中启动并使用JVM时：

    java -Xmx128m -Xms64m -Xmn32m -Xss16m Test  //假设测试的类是Test

在IDEA中启动JVM时： 

    打开 【IDEA 安装目录>>bin 】，其中有两个 vmoptions 文件，需针对不同的JDK进行配置：
    32 位：idea.exe.vmoptions
    64 位：idea64.exe.vmoptions


