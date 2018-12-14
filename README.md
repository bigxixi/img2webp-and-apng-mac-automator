# 序列帧转 webp + apng 动画小工具
这是个帮助转换 png 序列帧为 webp 和 apng 格式动画的 Mac Automator 服务。 
## 使用说明：
1. [下载`安装包`](https://raw.githubusercontent.com/bigxixi/img2webp-and-apng-mac-automator/master/%E5%BA%8F%E5%88%97%E5%B8%A7%E8%BD%AC%20webp%20%2B%20apng.pkg)，并正确安装本服务。  
2. 将 png 序列帧放在一个文件夹里，文件夹里不要有其他文件。  
3. 对着存放序列帧的文件夹 `右键` --> `服务` --> `序列帧转 webp + apng` ，根据提示操作即可。也可以单独导出 webp 或者 apng 格式。  
4. 可以选择多个序列帧文件夹进行操作，导出的 webp 或者 apng 动画存放在序列帧文件夹所在的目录。  

## 注意
 序列帧的命名请注意补零，位数对齐最大那个数字，例如假设有200张图，需要在个位前补2个0，十位前补1个0，即命名为 000.png、001.png … 010.png、011.png … 199.png，**不要**命名为 0.png、1.png …   
 

### 如果你安装了之前的版本
可能会有重复的右键菜单项，此时需要清理一下旧版，清理方法
finder - 前往 - 前往文件夹，输入 「/用户/你的用户名/资源库/Services/」，找到 「序列帧转 webp」这个服务然后删掉就好。  

### 界面
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/BGG.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/dialog.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/loop.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/fps.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/qualtiy.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/result_notify.png" width="70%" />
<img src="https://raw.githubusercontent.com/bigxixi/ReadMe-Resources/master/webp/result.png" width="70%" />



有问题可以联系西西：xixi@bigxixi.com  
2018.11.27  

————————  
## 本服务使用了以下软件：
img2webp  
https://developers.google.com/speed/webp/docs/precompiled

apngasm  
http://apngasm.sourceforge.net/

pngquant  
https://pngquant.org/
