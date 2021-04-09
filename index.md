## 简介

云测网盘正式版支持Windows及Mac系统，可实现上传，支持断点续传，导出CSV（用于标注平台创建标注任务），支持下载链接分享（可设定密码），支持导出文件摘要信息CSV（用于统计目录下重复文件），扩展工具箱，常用工具便捷使用。
项目人员需开通使用时，请联系技术团队，提供手机号码进行正式版使用权限开通 ：）

## 下载  (2.6.1版本)

[![](./images/windows.png)](http://ysdm.yscdn.testin.cn/pan/581242/download20210409/testin_pan_win_setup_2.6.1.exe?e=1649474260&token=zWgdjdRsH7WGyRTkxjc31KVUk1X8EoyE9qStHqaU:8RSBVxPoc7xpduESJx7MR_eQoCs=)
[![](./images/mac.png)](http://ysdm.yscdn.testin.cn/pan/581242/download20210409/testin_pan_mac_setup_2.6.1.dmg?e=1649474095&token=zWgdjdRsH7WGyRTkxjc31KVUk1X8EoyE9qStHqaU:Vi2MyRUVgxl6-C4Qv9LNSEJjO7s=)

## 说明文档 
[了解网盘功能，请查看文档](https://testindata.gitbook.io/label/pan/files)  

## Mac版注意事项
1.安装网盘客户端;  
2.如果电脑是macOS Catalina或macOS Big Sur版本，打开后可能存在安装损坏的提示;  
3.关掉提示弹窗，打开终端，输入如下命令，回车输入电脑密码(输入后不显示密码)，再回车，再次打开即可。  

sudo xattr -d com.apple.quarantine /Applications/云测网盘.app

## 更新记录  
2021/03/29 V2.6  
1、工具箱新增视频抽帧，支持间隔秒数以及间隔帧数抽帧，支持进度展示。  

2021/03/05  V2.5  
1、更新主页以及工具箱图标；  
2、导航栏双击返回上一层；  
3、工具箱本地排重，没有重复也会导出CSV，包含文件md5值；  
4、分享链接增加30天选项；  
5、导出CSV重名情况下累加格式由“（N）”改为“_N”。  

2021/01/29  V2.4  
1、新增工具箱选项，支持本地文件排重；  

2021/01/21  V2.3  
1、“有数云盘”更名为“云测网盘”；  
2、增加账户有效期；  

2021/01/06  V2.2  
1、导出CSV使用文件名称命名，同名CSV追加序号；  
2、右键菜单新增“导出文件摘要信息”，统计目录下是否有重复文件并标出行号，保存为CSV；  

2020/12/07  V2.1  
1、新增拖拽上传；  
2、支持文件选择历史记忆；  

2020/10/23  V2.0  
1、不需要使用管理后台（网站）进行批次号创建、分享、生成csv等配合工作，所有功能都集成到了客户端内，就可以完成数据上传、生成csv、分享等；  
2、启用了新版的UI，简化了操作流程，精简了构架，稳定性和速度上均有提升；  
3、支持Windows、Mac双系统
