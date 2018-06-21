# my-i3
我的自定义i3-wm快捷键配置, 默认配置的jkl;使用和vim的hjkl存在差异，使用上容易混淆，所以把快捷键改为统一意义。同时把冲突的 mod + h  改到c键上。
`顺便安利一句： i3-wm 平铺窗体管理器，真心好用.`

## 与默认配置的变更
- 把所有的 jkl; 变更为 hjkl
- 把 mod + h  变更为 mod + c

## 使用
1. 先安装附加软件
2. 安装字体
3. 把config文件的内容覆盖 ~/.config/i3/config 
4. 修改其中的两个图片路径

## 附加安装的软件
- rofi
- i3lock
- conky
- xclip
- scrot
- feh

## 字体安装方法
1. 拷贝字体文件夹到 /usr/share/fonts/目录下
2. 在目录执行fc-cache -fv
