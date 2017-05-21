olvlo项目是一个非常小的项目，非常低级的项目，从一点一点的入手，刘备不是说过吗，勿以善小而不为勿以恶小而为之。
在互联网时代，羊毛出在狗身上，猪来买单。这个项目分为几个层次：
	【低级】
	了解qqbot的语法知识
	会提取qq号码，提取1w足够
	使用sqlite存储qq号码
	了解web qq的协议，初步了解
	【中级】
	了解qqbot的高级知识
	【高级】
	会写qqbot的插件知识
	
（1）专注于qq软件协议的研究，专注于qq机器人的研究
（2）海豚群QQ
1569997592，湖北-喜欢，工作两年，做Web开发，常用语：这个...
2413476410，太原-记忆，工作两年
1510282279，天津-树林，工作三年，有点愤青，他妈的口头禅
（3）海豚群，每天要发言一次，关于公开课的内容，将埋点这个方案发挥好。
（4）查看网卡，见：http://www.pc841.com/article/20121230-10639.html
网卡是硬件，上面的网络通道是软件。
（5）了解到wireshark的，no time ,source destination protocol length info等列的含义
（6）qq的通信端口
腾讯QQ既通过TCP方式，又通过UDP方式来进行通讯。
TCP通讯方式分析
通讯端口分析
远程通讯端口范围: 80,443,8000,2679,2680。
UDP通讯方式分析
通讯端口分析
远程通讯端口范围: 8000。
（7）练习wireshark的过滤功能
（8）当前以公开课为主吧，搜索号码，群发邮件，破解邮件验证码问题。
	初步发1000封邮件
（9）.quit退出sqlite数据库
CREATE TABLE QQINFO(
   ID			INTEGER PRIMARY KEY     NOT NULL,
   NAME			TEXT	NULL,
   QQGROUP		TEXT	NULL,
   SEND_TIME	TEXT	NULL
);

INSERT INTO QQINFO VALUES (805246820,'春风',null,null);

