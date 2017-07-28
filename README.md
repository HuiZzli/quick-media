## quick-media
> 多媒体处理web服务
>
> mult-media process Web Service by FFMPEG & ImageMagic & SpringMVC
 
本项目为一个提供图片 + 音频 + 视频处理的Web项目，我们的目标是封装一套多媒体文件处理的公共类库，简化各种复杂的调用

利用 spring-boot 来提供http接口实现多媒体的操作


### 技术栈

- spring-boot 
- ffmpeg
- imageMagic
- zxing


### 已支持服务

1. 音频转码
   - 音频不同格式的相互转码

2. 二维码生成 & 解析
   - 支持logo
   - 支持logo样式 （圆角logo， 边框）
   - 支持二维码颜色设置
   - 支持探测图形颜色设置
   - 支持背景图
   - 支持base64格式的二维码图片
   - 支持二维码信息解析
   


### 待完成服务

1. 图片相关
    
    - 裁剪
    - 压缩
    - 旋转
    - 合成
    - 水印
    - 缩放
    - 格式转换
    - xxx
    
2. 视频相关


### 文档

- [音频转码服务说明](doc/audio.md)
- [二维码生成解析服务说明](doc/qrcode.md)
- [二维码服务拓展说明](doc/qrcodeExtend.md)