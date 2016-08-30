# himawari8
**实时抓取向日葵8号拍摄的气象卫星云图并设为壁纸**

#### 用途
> 每5min下载一次地球实时气象卫星云图（30min前），可用作壁纸

#### 说明
> 运行程序后将在电脑E盘建立E:\himawari8目录（若E盘不存在则在D、C盘，以下以E盘为例）用于存放图片

#### 设置方式
> 程序需用用到字体文件，可将喜爱的字体文件置于与程序同目录下，否则程序将从系统中选取字体文件



### 更新日志：

#### 0.4.1 2016/8/27 12：00
- 更正内存回收机制


#### 0.4.0 2016/8/25 23：38
- 实现程序开机自启功能


#### 0.3.0 2016/8/25 22：20
- 实现自动设置壁纸功能


#### 0.2.3 2016/8/25 02：50
- 加入内存回收机制，程序静默与工作均时大幅减少内存消耗
- 优化代码


#### 0.2.2 2016/8/24 23：20
- 禁止程序多开并提示，避免消耗电脑资源
- 优化代码


#### 0.2.1 2016/8/24 21：45
- 使用系统任意字体，避免华文行楷不存在
- 找不到字体时提示
- 更改图片时间信息，避免系统字体不支持中文符号


#### 0.2.0 2016/8/23
- 减少临时文件的使用
- 图片下载超时重连，提高下载效率
- 自动寻找本目录字体，若不存在则使用系统中的华文行楷
- 存放照片至指定目录E:\himawari8和E:\himawari8\wallpaper两个目录（若E盘不存在则在D、C盘，以下以E盘为例）
- 设置壁纸的更换方式为“幻灯片放映”，幻灯片相册为E:\himawari8\wallpaper，更改图片频率为1min/次，选择契合度为“适应”
- E:\himawari8用于存放历史图片，E:\himawari8\wallpaper用于存放当前壁纸


#### 0.1.1 2016/8/23
- 高分辨率图片下载并存于程序同目录
- 用指定字体添加照片时间信息


#### 0.1.0 2016/8/23
- 第一预览版
- 低分辨率图片下载并存于程序同目录
