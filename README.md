# AutoPlayWechatJumpGame
自动玩微信跳一跳游戏Java版，仅供技术研究使用，请勿用于非法用途，否则后果作者概不负责
![](pic.png) ![](jump.gif)

## 快速开始
1. 下载dist下zip包
2. 解压缩到任意目录
3. 双击start.bat启动
4. 点击“开始游戏” 
5. 适当调节运行时间系数
6. 如果连接手机错误，请先使用360手机助手连接一次手机

## 实现原理
1. 通过adb连接手机
2. 通过adb命令截屏抓取游戏页面
3. 计算出屏幕中黑棋到目标块的距离
4. 根据距离及时间系数计算出按压时间
5. 通过adb命令按压屏幕，实现跳到下一步

