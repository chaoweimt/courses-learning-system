# Linux 高端运维工程师
## 1 Linux基础入门
第一周  
第1章 Linux硬件基础  
1.1	计算机基础组成  
1.2	服务器核心组成讲解  
  
第2章 Linux发展历史  
2.1	操作系统组成  
2.2	linux发展过程  
2.3	linux核心知识讲解-GNU-GPL  
2.4	linux发行版本选择  
  
第3章 第1节 vmware创建虚拟机及Linux系统安装（centos )  
3.1	为何选择vmware软件学习linux  
3.2	vmware创建虚拟机过程  
3.3	centos安装过程  
3.4	企业级磁盘分区方案  
3.5	配置网络准备远程连接  
  
第3章 第2节 xshell软件优化-xshell连接服务器  
3.6	为何要远程连接  
3.7	xshell软件安装及基础优化  
3.8	通过xshell远程连接服务器  
第3章 第3节 SSH远程连接故障问题排查  
3.9	端口-IP-协议概念  
3.10 远程连接排错过程  
  
第二周  
第4章 第一关一大波命令及特殊字符知识考试题讲解  
4.1	linux系统基础规则  
4.2	linux基础命令  
4.3	一些特殊符号和快捷方式  
  
第5章 Linux系统优化  
5.1	添加普通用户账号   
5.2	关闭SELinux功能   
5.3	关闭iptables防火墙  
5.4	Linux中文显示设置（如何防止显示中文乱码）   
5.5	vmware快照使用方法   
  
第6章 Linux系统中目录结构知识精讲  
6.1	Linux目录特点  
6.2	挂载的概念-图解  
6.3	目录发展过程-略略讲  
6.4	Linux根下目录讲解-图解  
6.5	Linux核心文件和目录详解  
  
第三周  
第7章 第二关一大波命令及特殊符号知识考试题讲解  
7.1	PATH环境变量含义  
7.2	Linux启动过程  
7.3	Linux运行级别  
7.4	一大波命令  
  
第8章 Linux文件属性一大堆知识精讲  
8.1	inode和block简介  
8.2	文件类型  
8.3	linux基础权限介绍  
8.4	软硬链接  
8.5	文件删除原理  
8.6	用户和用户组简介  
8.7	Linux修改、访问、改变时间简介  
  
第四周  
第9章 Linux特殊符号-通配符与正则表达式  
9.1	之前课程遇到的特殊符号回顾  
9.2	什么是通配符  
9.3	常用的通配符讲解  
9.4	正则表达式用途  
9.5	基础正则详细讲解  
9.6	扩展正则详细讲解  
  
第10章 第三关一大波命令及重要知识考试题讲解  
10.1 练习正则表达式  
10.2 练习sed命令  
10.3 命令补充  
10.4 Linux知识，单引号,双引号,反引号  
  
第11章 Linux系统12位权限体系讲解  
11.1 对于文件来说rwx是什么  
11.2 对于目录权限rwx是什么  
11.3 umask与linux默认权  
11.4 企业生产场景网站目录设置权限的原则  
11.5 特殊权限suid,sgid,粘滞位讲解  
11.6 文件系统权限  

## 2 Linux系统管理进阶
第12章 Linux定时任务  
12.1 什么是定时任务  
12.2 定时任务分类-用户的，系统的  
12.3 定时任务软件分类：每个软件一句话  
12.4 定时任务格式及定时任务中的符号  
12.5 配置定时任务  
12.6 定时任务总结10箴言  
  
第13章 Linux用户管理  
13.1 回顾之前用户介绍  
13.2 与用户有关的文件及目录  
13.3 用户相关的命令讲解  
13.4 sudo用途  
13.5 简单例子  
13.6 项目sudo权限集中管理  
13.7 日志审计项目  
  
第14章 Linux磁盘与文件系统  
14.1 磁盘硬件简介  
14.2 磁盘接口详解  
14.3 磁盘mbr,分区表，主分区扩展分区，扩及分区讲解  
14.4 磁盘分区实战fdisk,parted  
14.5 文件系统讲解  

## 3 shell编程及计算机网络基础
第六周  
第15章 shell编程基础及提高、 sed与awk实战讲解  
15.1 Shell脚本入门  
15.2 Shell脚本的建立和执行  
15.3 Shell环境变量  
15.4 Shell局部（普通）变量  
15.5 Shell特殊变量  
15.6 Shell变量的子串  
15.7 变量的数值计算  
15.8 脚本中定义变量  
15.9 条件测试  
15.10 Shell函数  
15.11 if条件语句  
15.12 case结构条件句  
15.13 循环语句(while/until/for)  
  
第16章 计算机网络基础  
16.1  OSI-7层模型  
16.2  TCP/IP三次握手四次断开  
16.3  网络连接11种状态  

## 4 Linux网络服务
第七周  
第17章 期中架构体系介绍期中架构环境准备  
17.1 期中架构绘图讲解  
①. 架构组成部分  
②. 架构部署流程  
③. 架构环境准备（IP地址规划 主机名规划）  
17.2 期中架构虚拟机配置  
①. 虚拟机网络配置说明  
②. 模板系统网卡配置配置  
17.3 期中架构系统优化  
17.4 期中架构虚拟机功能介绍  
①. 快照功能说明  
②. 克隆功能说明  
  
第18章 rsync备份服务课程  
18.1 rsync备份服务介绍  
①. Rsync增量复制概念说明      
②. Rsync软件实质功能作用(等价 cp scp rm ls)  
18.2 Rsync软件特性说明  
18.3 Rsync软件工作场景说明  
①. 定时任务+rsync  
②. 实时同步+rsync  
18.4 Rsync软件参数说明  
18.5 Rsync工作方式说明（本地模式/隧道模式/守护进程模式）     
18.6 Rsync守护进程模式部署过程     
①. Rsync服务端部署过程  
②. Rsync客户端部署过程  
18.7 Rsync软件客户端访问原理  
18.8 Rsync软件服务扩展知识讲解  
①. rsync多模块配置说明  
②. rsync客户端创建多级目录  
③. rsync排除功能说明  
④. rsync访问控制配置说明  
⑤. rsync无差异同步功能  
⑥. rsync列表功能说明  
18.9 Rsync软件排错原理  
  
第19章 全网架构备份项目  
19.1 全网备份项目介绍说明  
①. 全网备份项目部署需求说明  
②. 全网备份项目部署规划说明  
③. 全网备份项目部署实施过程  
  
第八周  
第20章 NFS网络文件共享服务课程（上）  
20.1 NFS网络文件系统介绍  
20.2 NFS网络文件系统作用  
①. 网络共享文件系统由来  
②. 网络文件系统实现方式（软件实现方式/硬件实现方式）  
20.3 NFS共享文件服务工作原理  
①. 客户端挂载共享目录说明  
②. Windows共享目录使用过程说明  
20.4 NFS共享系统挂载命令简介  
20.5 NFS共享系统知识原理说明  
①. RPC服务概念介绍  
②. RPC服务工作原理  
③. RPC服务出现原因  
④. NFS工作原理深入理解（绘图）  
20.6 NFS共享服务系统部署过程  
20.7 NFS共享服务软件进程说明  
20.8 NFS共享服务软件排错思路  
20.9 NFS共享服务软件编写说明（exports配置文件编写参数说明）  
20.10 NFS共享服务自动挂载方式  
20.11 企业生产场景NFS exports配置案例（3个常见配置案例说明）  
  
第21章 NFS网络文件共享服务课程（下）  
21.1 NFS共享服务常用权限参数  
21.2 NFS共享服务用户映射关系（相关映射关系参数说明）  
21.3 NFS共享服务用户权限问题（重要两点涉及用户权限）  
21.4 NFS共享服务企业案例实践（配置实操练习）  
21.5 NFS共享服务权限知识梳理  
21.6 NFS共享服务重要文件命令  
21.7 NFS服务客户端挂载命令详解  
21.8 NFS服务客户端挂载权限参数  
21.9 NFS服务客户端挂载常用参数（文件系统只读案例说明）  
21.1 NFS共享服务优化方法小结  
21.2 NFS共享服务优点缺点介绍  
  
第22章 inotify+rsync实时同步服务课程sersync实时同步服务课程  
22.1 实时同步服务知识介绍  
①. 实时同步原理说明  
②. 实时同步工作方式  
22.2 实时同步项目部署过程（inotify+rsync）  
22.3 实时同步项目部署过程（sersync）  

## 5 Ansible批量管理与维护
第九周  
第23章 ansible基础部分课程  
23.1 ssh+key共享密钥部署流程  
23.2 ssh+key公钥批量分发步骤  
23.3 ssh+key公钥批量管理实现  
23.4 ansible软件概念介绍  
23.5 ansible软件安装部署  
23.6 ansible软件常用模块使用  
  
第24章 ansible进阶部分课程  
24.1 ansble软件扩展模块使用  
24.2 ansible软件剧本编写说明  
24.3 ansible软件剧本编写实践  

## 6 Linux重要网络服务
第十周  
第25章 HTTP基础原理知识课程  
25.1 HTTP相关服务介绍  
25.2 HTTP协议原理介绍  
①. 请求报文结构说明  
②. 响应报文结构说明  
25.3 HTTP资源概念说明  
①. 静态页面与动态页面知识  
②. 伪静态页面知识介绍  
③. URL与URI概念说明  
25.4 网页度量值概念介绍  
25.5 网页度量值度量方法  
25.6 网站并发连接说明  
25.7 网站统计信息排名  
25.8 网站web软件常见说明  
  
第26章nginx网站服务课程（上）  
26.1 nginx软件介绍说明
26.2 nginx软件的特点或优势
26.3 nginx软件的企业功能应用
26.4 nginx软件的动态访问瓶颈
26.5 nginx软件的编译安装步骤
26.6 nginx软件的编译安装常见错误说明
26.7 nginx软件使用过程中深入说明
26.8 nginx软件静态页面编写过程
26.9 nginx配置文件内容信息精讲
  
第27章 nginx网站服务课程（下）  
27.1 nginx配置文件实践配置讲解  
①. 虚拟主机概念说明  
②. 多虚拟主机配置说明  
27.2 nginx虚拟主机类型配置说明  
①. 基于域名虚拟主机配置方式  
②. 基于地址虚拟主机配置方式  
③. 基于端口虚拟主机配置方式  
27.3 nginx配置虚拟主机步骤总结  
27.4 nginx排错过程思路总结说明  
27.5 nginx软件常用扩展功能说明  
①. nginx配置文件规范化管理  
②. nginx域名别名功能实践说明  
③. nginx状态模块功能实践说明  
27.6 nginx日志功能说明  
①. 错误日志配置说明  
②. 访问日志配置说明  
③. 访问日志信息说明  
27.7 nginx软件location模块作用实践说明  
27.8 nginx软件rewirte模块作用实践说明  
  
第十一周  
第28章 LNMP架构服务搭建  
28.1 Linux安装优化注意事项回顾  
28.2 Nginx软件服务编译配置回顾  
28.3 Mysql软件服务安装配置步骤实践  
28.4 PHP软件服务安装配置步骤实践  
28.5 Nginx软件与PHP软件结合配置实践与测试验证  
28.6 PHP软件与MySQL软件结合配置实践与测试验证  
  
第29章 nginx负载均衡深入透彻  
29.1 集群是什么？  
29.2 集群分类  
29.3 常用的集群软硬件介绍及选型  
29.4 搭建负载均衡nginx  
29.5 负载均衡与反向代理区别  
29.6 负载均衡模块的说明  
29.7 负载均衡的实战部署  
  
第30章 keepalived高可用深入透彻  
30.1 Keepalived高可用软件介绍  
30.2 Keepalived高可用服务搭建准备  
30.3 Keepalived高可用服务单实例实战  
30.4 Nginx负载均衡配合Keepalived服务案例实战  
30.5 Keepalived高可用服务器对裂脑问题  
30.6 常见问题及解决   
30.7 keepalived总结  

## 7 Linux中小规模集群构建与优化
第十二周  
第31章 zabbix监控  
31.1 Zabbix简介  
31.2 系统环境  
31.3 YUM安装Zabbix 3.0  
31.4 网页配置  
31.5 中文配置  
31.6 Zabbix Agent客户端安装使用  
31.7 查看监控数据  
31.8 解决中文乱码  
31.9 简单自定义监控  
31.10 监控报警  
31.11 监控可视化  
31.12 zabbix共享模版  
31.13 监控期中架构集群  
31.14 SNMP监控  
31.15 自动注册和自动发现  
31.16 分布式监控  
  
第32章 kickstart 批量自动安装系统  
32.1 简介  
32.2 安装DHCP服务  
32.3 安装TFTP服务  
32.4 配置HTTP服务  
32.5 配置支持PXE的启动程序  
32.6 预热之手动网络安装  
32.7 创建ks.cfg文件  
32.8 无人值守自动安装  
32.9 安装完成后验证  
  
第33章 cobbler  
33.1 Cobbler介绍  
33.2 Cobbler安装配置  
33.3 Cobbler的WEB管理  
  
第34章 memcached原理及部署/作为缓存及session会话共享  
34.1 Memcached简介  
34.2 Memcached原理及优点  
34.3 Memcached在企业中使用场景  
34.4 Memcached分布式缓存集群  
34.5 Memcached安装使用  
34.6 Memcache客户端  
34.7 wordpress使用memcache缓存  
  
第十三周  
第35章 Centos7系统自行安装/centos6与7区别  
35.1 区别1：网卡名称eth0和enp5s0  
35.2 区别2：网络配置相关命令  
35.3 区别3：主机名等配置文件  
35.4 区别4：兼容的 /etc/rc.local  
35.5 区别5：运行级别Runlevel  
35.6 区别6：管理服务  
  
第36章 tomcat java应用服务/nginx配合tomcat服务部署及优化  
36.1 Tomcat简介  
36.2 Tomcat安装  
36.3 Tomcat配置文件  
36.4 WEB站点部署  
36.5 Tomcat多实例及集群架构  
36.6 Tomcat监控  
36.7 Tomcat安全优化和性能优化  
  
第37章 代码管理与上线  
37.1 svn  
37.2 代码上线项目案例  

## 8 虚拟化-云计算
第十四周  
第38章 机房知识  
38.1 企业运维IDC机房及带宽维护知识精讲  
38.2 生产环境DELL R730服务器服务器实战配置（远程控制卡/raid等）  
  
第39章 企业阿里云云计算集群实战精讲  
39.1 入门介绍  
39.2 基础概念  
39.3 实战部署lnmp-wordpress   
  
第40章 KVM虚拟化企业级实战  
40.1 KVM简介  
40.2 KVM使用  
40.3 虚拟机的管理命令  
40.4 磁盘文件格式介绍  
40.5 克隆虚拟机  
40.6 快照  
  
第41章 老男孩高薪实战-运维班期末高薪就业指导  
41.1 运维班期末高薪就业指导1  
41.2 运维班期末高薪就业指导2  
41.3 运维班期末高薪就业指导3  