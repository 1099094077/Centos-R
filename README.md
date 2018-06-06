# Centos-R
提供R语言的Centos离线安装包及依赖
说明：
1、R-core跟R-core-devel及其所有依赖通过epel源下载
2、目前只有基于Centos7的64位R安装包，版本号为3.4.4，以后会
   不断更新，也考虑支持以前版本的源码一键编译、安装脚本（后期更新）。
3、离线安装方式：切换到centos7-R3.4.4目录下，然后执行sudo yum localinstall *.rpm
4、建议实验环境测试后再进行生产环境部署。
