## 1.0.6 (2020-02-17)
* 新增：支持全埋点版本，自动采集 $MPLaunch（小程序启动)、$MPShow（小程序显示）、$MPHide（小程序进入后台）、$MPViewScreen（小程序页面浏览）、$MPClick（小程序元素点击）五个预置事件；
* 优化：去除 sensorsdata_conf.js 文件，使用 setPara() 方法初始化配置参数；

## 1.0.5
* 统一格式化所有小程序的预置属性$os的取值，从系统默认的ios改成了iOS，android或Android

## 1.0.4
* 设置网络请求时的 dataType 为 text

## 1.0.3
* 修正了扫描普通二维码打开小程序代码报错的问题

## 1.0.2
* 更新发送请求的方式，兼容 my.request 和 my.httpRequest

## 1.0.1
* 增加了预置事件 $MPLaunch, $MPShow, $MPHide