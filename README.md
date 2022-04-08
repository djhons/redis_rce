# redis_rce
windows redis主从复制 具体分析请看[redis主从复制的一些利用](https://djhons.com/2021/10/29/61.html)

仅仅作为安全研究使用，请勿用于非法渗透。

1、在测试环境中导致了redis服务崩溃，目前已修好，但不保证在实际环境中不会出现这种问题，请在使用前使用对应环境测试并小心使用。

2、部分windows server中会出现和redis6一样找不到动态链接库的情况，目前不知道是什么原因。可以使用config set dir \*命令设置目录后尝试。或许能成功

![d65b7007e382fc1b30428591cfd2b5d](https://user-images.githubusercontent.com/102639729/162352278-ffbad8d1-5266-4289-a01b-2b9c3e33d441.png)
