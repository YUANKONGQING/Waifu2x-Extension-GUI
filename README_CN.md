# Waifu2x-Extension-GUI
#### 下载: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/releases/latest
#### 更新日志: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Change_log.md
#### 捐赠名单: https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Donate_list.md
#### 如果README内的图片无法正常加载,请[打开此链接查看码云内存储的README.md](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/blob/master/README.md)或者合法的连接国际网络后刷新页面, 当然您也可以[按照这个教程来尝试修复github图片加载的问题](https://github.com/AaronFeng753/Github_dns_hosts#github_dns_hosts).
# Waifu2x-Extension-GUI是什么?
 借助深度卷积神经网络对`图片` & `GIF` & `视频`进行超分辨率放大(即放大与降噪).

基于 `Waifu2x-ncnn-vulkan` 和 `Waifu2x-converter` . 

借助waifu2x-ncnn-vulkan, Waifu2x-Extension-GUI 可以借助任何支持`Vulkan`的显卡进行运算,即便是Intel的集成显卡. 

如果您的显卡不支持vulkan, 您还可以将引擎切换为Waifu2x-converter,同样可以很快的对图像进行放大与降噪.(已集成在release内)

![mainwindow](/Screenshot/mainwindow_cn.jpg)

#### 已经在 `AMD` RX 550, `NVIDIA` GeForce GTX 1070 和 `Intel` UHD 620 上通过测试.

# Features
- Easy to use GUI interface.
- Achieved with `waifu2x-ncnn-vulkan`, `waifu2x-converter` and `Anime4K`.
- Support both `2D Anime-style` image and `3D Real-life` image
- Support 1x/2x/3x/4x/..../999999999x magnification
- Batch enlarge still `images` and `GIF` dynamic images (Waifu2x-ncnn-vulkan & Waifu2x-converter)
- Batch enlarge `video` files (Waifu2x-ncnn-vulkan & Waifu2x-converter & Anime 4k)
- Save the enlarged image target as .jpg
- Lossless compression of .jpg images after the target is saved
- Optimize enlarged GIF dynamic images to reduce space usage
- Display processing progress and remaining time
- Smart selection of models
- Batch process pictures, GIF and video files.
- Flexible multi-thread management
- Continually updated
- Compatibility test
- And more

# Samples
### **`Image`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/image

### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

### **`GIF`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/gif

#### Original 2D Anime Imgae 480x300 (.jpg 93.2 KB):
![Original Imgae](/Samples/image/Original_[480x300].jpg)

#### After 8x magnification, level 3 denoise and compress 3840x2400 (.jpg 525 KB):
![Scaled Imgae](/Samples/image/Waifu2x_8x_[3840x2400].jpg)

#### Comparison
![Comparison](/Samples/image/Comparison.png)

#### Original 3D Real-life Imgae 800x535 (.jpg 81.4 KB):
![Original Imgae](/Samples/image/deer.jpg)

#### After 4x magnification, level 2 denoise and compress 3200x2140 (.jpg 881 KB):
![Scaled Imgae](/Samples/image/deer_Waifu2x.jpg)

#### Original GIF 500 x 372 (493 KB):
![Original GIF](/Samples/gif/2_original.gif)

#### After 2x magnification, level 2 denoise and gif optimize 1000 x 744 (3.77 MB):
![Original GIF](/Samples/gif/2_waifu2x_compressed.gif)

### `Github doesn't support play video online, pls check link below:`
### **`Video`** : https://github.com/AaronFeng753/Waifu2x-Extension-GUI/tree/master/Samples/video

# How to fix compatibility issue :
#### waifu2x-ncnn-vulkan: Re-install gpu driver or update it to the latest.
#### waifu2x-converter: Buy a new computer.
#### Anime4k: Install the latest JDK and JRE

# Integrated component(In releases):
- waifu2x-ncnn-vulkan version Nov 4, 2019

- Anime4K Java v0.9 Beta

- ffmpeg version 4.2.1

- gifsicle version 1.92

- Waifu2x-converter version: 2015-11-30T02:17:24

- ImageMagick 7.0.9-12-portable-Q16-x64

# Credits:
- waifu2x-ncnn-vulkan: https://github.com/nihui/waifu2x-ncnn-vulkan

- FFmpeg: https://ffmpeg.org/

- Gifsicle: https://www.lcdf.org/gifsicle/

- Anime4K: https://github.com/bloc97/Anime4K

- Waifu2x-converter: https://github.com/WL-Amigo/waifu2x-converter-cpp

- ImageMagick: http://www.imagemagick.org/

- Icons made by : Freepik (https://www.flaticon.com/authors/freepik) From Flaticon : https://www.flaticon.com/

# `Donate`
### [Donation list](https://github.com/AaronFeng753/Waifu2x-Extension-GUI/blob/master/Donate_list.md)
#### 如果donate(捐赠)二维码图片无法正常加载,请[打开此链接查看](https://gitee.com/aaronfeng0711/Waifu2x-Extension-GUI/raw/master/donate.jpg)或者合法的连接国际网络后刷新页面, 当然您也可以[按照这个教程来尝试修复github图片加载的问题](https://github.com/AaronFeng753/Github_dns_hosts#github_dns_hosts).
![donate](/donate.jpg)