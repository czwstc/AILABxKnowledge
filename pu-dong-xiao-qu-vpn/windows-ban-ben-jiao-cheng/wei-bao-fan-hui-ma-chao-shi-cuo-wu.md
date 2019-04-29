# Win10 链接报返回码超时错误

问题的根源是Win 10 的 驱动程序强制签名启动。

1. 使用传统模式启动Win10 （Bios中选择Legacy启动）
2. 进入系统，关闭强制签名启动。

CMD命令输入

**`bcdedit.exe /set nointegritychecks on`**

 ****

**参考：**[**https://www.ithome.com/html/win10/196402.htm**](https://www.ithome.com/html/win10/196402.htm)\*\*\*\*

