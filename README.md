### Canvas 生成海报
clone 到本地，无需安装，直接打开index.html 背景图调用的是国外网站会有很长的加载时间，请勿刷新。


- 替换images/文件夹下的logo图片和二维码图片
- 背景图片是调用 https://unsplash.com/https://unsplash.com/ 网站上的，可以用tag参数调用上面的分类，如?tag=wallpapers 或 tag=nature,由于是国外网站加载速度非常慢，也可以用bg参数指定背景图片如 ?bg=http://www.xxx.com/bg.jpg
- 根据手机大小背景图片会居中截取一块适应当前屏幕的
- 未做电脑端适配，电脑排版会乱
- 为了防止在绘图时图片未载入导至有部分空白，加载图片用loadImage方法
- 鸡汤文字固定在代码里，也可以动态去获取
