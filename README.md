## b站视频教程：
(1)linux 我的常用好软件推荐：https://www.bilibili.com/video/BV1vL4y1n79N

(2)linux 我的常用好软件推荐：https://www.bilibili.com/video/BV1S44y177jq

linux kde 美化和常用的软件：https://www.bilibili.com/video/BV14R4y1x79V

终端文件管理器(ranger)配置使用：https://www.bilibili.com/video/BV1ER4y1F72A

(1)linux i3wm使用安装和使用：https://www.bilibili.com/video/BV1CZ4y1C7TA

(2)linux i3wm使用rofi搜索工具配置美化：https://www.bilibili.com/video/BV1vu411k7JZ




## 效果图

## i3wm

下面用了nyancat，cmatrix，sl，ranger

![image-20211031231109293](https://cdn.jsdelivr.net/gh/Zhao-sai-sai/Picture/image-20211031231109293.png)

## kde

![](https://cdn.jsdelivr.net/gh/Zhao-sai-sai/Picture/320.gif)

## 说明

叫这个配置文件复制到对应的文件就可以使用了，kde和i3wm按照下面的安装就可以了

kde可能会依赖其他的东西可以直接自行安装

## fzf安装

安装fzf

```sh
sudo apt-get install fzf 
```

## ranger安装

```sh
git clone https://github.com/ranger/ranger.git
cd ranger
sudo make install
sudo python3 setup.py install --optimize=1 --record=install_log.txt
```

## 效果
![qqqqq](https://cdn.jsdelivr.net/gh/wzass/zp/qqqqq.png)


## i3wm的配置

里面的程序会调用的工具



## 通知守护程序

安装dunst

```sh
sudo pacman -S dunst
```



## 安装polybar

```sh
git clone https://aur.archlinux.org/polybar.git
cd polybar
makepkg -si 
```

## 屏幕锁

用的是i3lockr

安装

```sh
wget https://github.com/owenthewizard/i3lockr/releases/download/v1.1.0-docfix/i3lockr
chmod +x i3lockr
或者直接放到环境变量里面
sudo mv i3lockr /usr/local/bin
```



## 网络连接

用的nm-applet

安装

```sh
sudo pacman -S  network-manager-gnome
```

## 终端安装

我用的是konsole

```sh
sudo pacman -S  konsole
```



## 主题

用的是`lxappearance`

安装

```sh
sudo pacman -S lxappearance
```



## kde的一些插件的安装

里面的配置文件就是用的下面的其中的配置文件

##  latte-dock安装

安装

```
sudo pacman -S  latte-dock
```

## Plasma样式美化

我用的是`WhiteSur-alt `

你们可以去下载

![image-20210316205800488](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210316205800488.png)

## 插件

> `panon`有声音就会动的一个插件

   他依赖

   ```
   sudo pacman -S qt5-websockets python-docopt python-numpy python-pyaudio python-cffi python-websockets libpackagekit-glib
   ```

   ![image-20210317082623220](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317082623220.png)

>  `Netspeed`流量监控

   ![image-20210317083316061](/home/zss/.config/Typora/typora-user-images/image-20210317083316061.png)

>  `Reversal`小米图标

   ![image-20210317083508762](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317083508762.png)

>  `System load `系统监控

   ![image-20210317083923950](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317083923950.png)

>  `Monitor`桌面系统监控

   

   ![image-20210317084536275](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317084536275.png)

>  `Layan`光标

   ![image-20210317092435050](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317092435050.png)

>  `cherry`窗口装饰

    ![image-20210317092747242](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317092747242.png)

>  `Evergarden`欢迎界面

   ![image-20210317092942561](https://cdn.jsdelivr.net/gh/wzass/zp/image-20210317092942561.png)

