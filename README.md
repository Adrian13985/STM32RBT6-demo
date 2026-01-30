无聊


开发日志
终于在clion上跑起来了
试过cubeide vscode 都失败了
在clion里 配置了cmsis-dap.cfg  加了一行
adapter driver cmsis-dap
意思是启用v1协议（不懂就去看这个文件 很简单）

开发日志2
一个下午卡在编译上了wwwww
总结一下
Cmake配置文件记得不要选Ninja 直接让Cmake决定即可 直接Debug预设就行了 具体原因不知道