Windows 7 环境准备
==================

1. 在[官方下载页][1]，下载最新发布版本，当前撰写日为2013/8/25，版本 1.0.5。
2. 最省心的方式即可下载 [Windows Installer][2]，适合全新的安装。
3. 安装完成后即可通过 USB 连接线，和 PC 连接上 Arduino 进行测试。
4. 启动 Arduino 应用程序。
5. 界面支持中文，设置方法： `File` > `Preferences` > `Editor language` > `简体中文（Chinese Simplified）`.
6. 重启 Arduino 。
7. 选择 `文件` > `示例` > `01.Basics ` > `Blink ` 后，可以看到示例代码。
8. 确认 `工具` > `板卡`  所选择的是  `Arduino Uno` 。
9. 确认 `工具` > `串口`  所选择的类型和 windows 设备管理器下显示的 `Arduino Uno端口（COMxxx）`  中的 COM 类型一致，如 COM3。
10.点击下载（确切翻译为“上传”）。此时板卡上 RX 和 TX 会开始闪烁。之后，编辑界面显示“下载完毕”。即可看到 13 针脚（L）的 橘色 LED 灯闪烁。
11.变更代码中  delay(1000);中的数值，即可看到按毫秒（1000毫秒 = 1秒）作用于前一句的延迟响应。




[1]:http://arduino.cc/en/Main/Software "下载页"
[2]:http://arduino.googlecode.com/files/arduino-1.0.5-windows.exe "Windows Installer"