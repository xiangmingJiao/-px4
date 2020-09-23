# -px4
简述px4环境搭建的过程，基于ubuntu18.04  ros版本melodic 

1.CSDN和很多github项目推荐使用官方推荐的安装脚本
链接：https://dev.px4.io/v1.10/zh/setup/dev_env_linux_ubuntu.html
2.进入链接界面之后不要直接点上面的ubuntu.sh 往下翻页面，下面会有具体的安装步骤
2.1 运行下面两条命令 下载ubuntu.sh文件和requirements.txt文件 
    wget https://raw.githubusercontent.com/PX4/Firmware/v1.10.0/Tools/setup/ubuntu.sh
    wget https://raw.githubusercontent.com/PX4/Firmware/v1.10.0/Tools/setup/requirements.txt
2.2 运行下面两条命令
     bash
     source ubuntu.sh
然后安装成功会重启

注：如果不小心点进了页面上面的ubuntu.sh，并且使用wget当前页面的网址的话 ，在source ubuntu.sh文件时会报错误： “bash: ubuntu.sh: 行 6: 未预期的符号 `newline' 附近有语法错误”
此时将主目录下下载的ubuntu.sh文件删除，然后按照上述第二步所示步骤，便可以解决。
