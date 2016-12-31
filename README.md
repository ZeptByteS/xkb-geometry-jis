### XKB geometry files for JIS keyboards
Ubuntu Gnome 16.04上で作成した設定ファイルです. 日本でよく使われるJIS配列用のgeometryファイルが見当たらなかったため,自作しました.

この設定ファイルを使用するには, ファイルをコピーし,```/etc/default/keyboard``` に下記の ```XKBMODEL=model-name``` を追加し,再起動します.


Configuration files that created on Ubuntu Gnome 16.04. Because I could not find the geometry file for JIS keyboards which is commonly used in Japan, I made it myself.

To use this configuration file, copy files, add ```XKBMODEL=model-name``` to ```/etc/default/keyboard``` and reboot.

Example:

例:

    BACKSPACE=guess
    XKBLAYOUT=us
    XKBVARIANT=dvorak
    XKBMODEL=jis91_numlk

---
### XKBMODEL=jis108

![](https://github.com/ZeptByteS/xkb-geometry-jis/blob/master/pictures/jis108.png)
### XKBMODEL=jis109
![](https://github.com/ZeptByteS/xkb-geometry-jis/blob/master/pictures/jis109.png)
### XKBMODEL=jis91
![](https://github.com/ZeptByteS/xkb-geometry-jis/blob/master/pictures/jis91.png)
### XKBMODEL=jis91_numlk
![](https://github.com/ZeptByteS/xkb-geometry-jis/blob/master/pictures/jis91_numlk.png)
