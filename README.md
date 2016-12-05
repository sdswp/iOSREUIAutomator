# iOSREUIAutomator
基于越狱环境的iOS App UI测试框架，测试从Appstore下载的应用，无需反编译、hook。
##iOSREUIAutomatorDemo.deb
安装前请先安装substrate，rocketbootstrap。

demo测试循环用例：杀死appstore-->等待5秒-->打开appstore->检测首页显示时间-->检测搜索结果显示时间
##使用
24循环测试，可以直接测试从AppStore下载的应用，无需反编译、hook应用，直接编写测试用例测试。
##运行环境
iPhone越狱,系统：iOS 7.0-9.2，依赖Cydia应用：substrate，rocketbootstrap（请先安装）
##系统功能
###点击
1. 坐标点击
2. 随机点击
3. 跟踪点击

###滑动
1. 屏幕滑动

###拖动
1. 控件拖动

###输入
1. 输入任意字符

##业务功能
1. 24小时不间断测试
2. 测试应用启动时间
3. 测试每个UI展示耗时（精确到50毫秒）
