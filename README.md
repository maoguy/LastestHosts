# 使用方法

将hosts文件下载到本地替换以下目录的hosts文件即可

windows:

>C:\Windows\System32\drivers\etc

OSX:

>/private/etc

修改hosts后生效的方法：

	Windows
		开始 -> 运行 -> 输入cmd -> 在CMD窗口输入
			ipconfig /flushdns


	Linux
		终端输入
			sudo rcnscd restart

	Mac OS X
		终端输入
			sudo killall -HUP mDNSResponder

	通用方法
		拔网线(断网) -> 插网线(重新连接网络)
