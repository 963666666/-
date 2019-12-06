# -
TCP/IP
======
OSI分层，已经各个层之间的协议
------
	*应用层
	邮件点击发送就进入了应用层，应用层还包括接收方无法接受这类问题的处理（邮件发送，文件传输，远程连接）
	*表示层
	数据格式的转换，按照规定格式的编码转化成相应的数据
	*会话层
	决定以某种方式连接（传输五封邮件，可以建立五次连接发送，可以建立一次连接发送，同时建立五次连接一起发送）
	*传输层
	建立连接或断开连接的处理，主机之间创建逻辑上的通信连接，确认数据包传输，没有传输成功，进行重发
	*网络层
	网络节点的管理和选择
	*数据链路层
	通过传输介质互联的设备之间进行数据处理
	*物理层
	将包含MAC地址信息的首部附加到网络层转发过来的数据上，将其发送到网络

面向有连接和面向无连接
------

电路交换和分组交换
------
	*电路交换
	独占网络
	*分组交换
	将要发送的数据分成多个数据包，按照一定的数据分别发送，提高通信线路的利用率
根据接收端数量分类
------
	*单播
	*广播
	*多播
	*任播
地址的层次性
------
	*MAX地址 没有层次性
	*IP地址 有层次性
	
######TCP/IP
#####IP协议