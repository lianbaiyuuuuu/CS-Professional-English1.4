# CS-Professional-English1.4
## 计算机网络知识点总结-第wu章：网络层
#### 本章知识图
![alter ](https://img-blog.csdnimg.cn/2019112816480632.JPG?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80MzA5MzQ4MQ==,size_16,color_FFFFFF,t_70)
#### 运输层的两个主要协议
>1. **两个主要协议：**
>	+ 用户数据报协议(UDP)
>	  - *在传送数据之前不需要先建立连接，远地主机收到UDP报文后，不需要给出确认，UDP不提供可靠交付，但某些情况却是最有效的工作方式*
>	+ 传输控制协议(TCP) 
>	  - *提供面向连接的服务，在传送数据前先建立连接，数据传送结束后要释放连接；TCP不提供广播或多播服务；TCP提供可靠的、面向连接的运输服务，因此增加了很多开销*
>2. ~~UDP与IP数据报的区别：~~
>	+ IP数据报要经过互联网中许多路由器的存储转发
>	+ UDP用户数据报是在运输层的端到端抽线的逻辑信道中传送的
>	+ TCP报文是在运输层抽象的端到端逻辑信道中传送，这种信道是可靠的全双工信道

***
| 应用 | 应用层协议 | 传输层协议 |
| :----:| :----: | :----: |
| 名字转换 | DNS | UDP |
| 文件传送 | FTP | TCP |

***
#### 代码块 Syntax highlighting

    ```python
    #!/usr/bin/env python3
    print("Hello, World!");
    ```
	
***
内容转载于 [计算机网络知识点总结-第五章：传输层](https://blog.csdn.net/weixin_43093481/article/details/86684098)
