# util工具库,C/C++代码分离,可运行于linux,windows,mac平台，提供实用类和方法.

C提供基本数据结构(list,rbtree,hashtable,tree),mt19937随机数,可靠UDP接口,json格式解析,各个系统平台API/crt封装以实现跨平台(包括文件,套接字,进程线程操作,原子操作,锁,io通知,内存,时间,字符串,错误码统一,少量常用的编解码,杂项信息统计).

C++部分在C的基础上实现定时器,消费者,网络io,日志,异常,缓存,数据库等操作.

可直接集成到项目中,不与其他部分冲突.

编译需注意:

1.linux下需要安装一下uuid库,openssl.
