## 屏幕尺寸
+ 指屏幕的对角线的长度，单位英寸

## 屏幕分辨率(即物理像素)
+ 横纵向上的像素点数。单位px，1px = 1个像素点(这里的像素指物理像素)  横向像素 * 纵向像素(1960*1080)

## 物理像素(设备像素)

## css像素  
- css像素抽象单位，主要使用在浏览器上(web页面)； css像素转为物理像素。

## 物理像素与css像素的关系
+ 一个css像素占据多少个物理像素与屏幕有关系
- 注意css像素与物理像素的关系是靠浏览器厂商在维护，而非设备厂商
- 对于高清屏来说 一般是4倍(1个物理===4个css像素)

## 设备独立像素(浏览器中的真机模仿)  css像素转向物理像素很重的一个媒介
* 设备独立像素 可以认为是计算机坐标系统中的一个点， 由相关系统转换为物理像素

## 像素比  设备物理像素和设备独立像素的比例   像素比 = 一个方向上占满一块屏幕的物理像素个数 / 一个方向上占满一块屏幕需要的设备独立像素的个数
+ 物理像素即设备分辨率(横向像素 * 纵向像素)   注意：像素比是个数比，而不是面积比
+ 设备独立像素(浏览器中手机模式的像素)
- devicePixelRatio(dpr) = 物理像素 / 设备独立像素
+ 可以通过window.devicePixelRatio类获取 
* 当写上meta标签后，width = device-width，使css像素与设备独立像素连接起来(即css像素等同于设备独立像素)   1css像素 = 4 倍物理像素  这里指面积



## 位图像素(图片的大小尺寸)  1个位图像素对应一个物理像素，图片才能完美清晰的展示