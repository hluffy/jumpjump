# python微信跳一跳		
1. adb shell screencap 获取屏幕截图
2. adb pull /sdcard/screen.png 下载图片到电脑当前文件夹下
3. adb shell input swipe %d %d %d %d %d 点击屏幕的横坐标 点击屏幕的纵坐标 离开屏幕的横坐标 离开屏幕的纵坐标 点击时间