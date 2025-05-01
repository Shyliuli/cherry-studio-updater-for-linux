## English:


### Cherry Studio Updater for Linux
- Cherry Studio updater for Linux, Cherry Studio Linux client update script
- Originally for personal use, now shared to make it easier for everyone
#### How to Use
- Open the cherry_update script, enter your proxy address (if needed), configure other variables according to your requirements, save it to any PATH directory (for example, /usr/bin), then run
```
chmod +x /path/to/cherry_update
```
After that, just run cherry_update in the terminal
- Oh, right, you might also need to create a desktop file
```
Desktop Entry
Categories=Development;
Exec=/opt/cherry/cherry-studio.appimage
Icon=cherry-studio
Cherry Studio
false
Application
```
Note: you need to place the icon file cherry-studio.png into
```
/usr/share/icons/hicolor/48x48/apps/cherry-studio.png
```
For compatibility, I suggest you place the icons in 16x16, 32x32, 64x64, 128x128, and 256x256 folders and scale them to the appropriate sizes.
Of course, if you want to save effort, you can also place them directly in /usr/share/pixmaps/ and then hope the desktop scales them correctly

## Chinese:

### cherry-studio-updater-for-linux
- cherry-studio updater for linux cherry-studio linux客户端更新脚本
- 之前是个人自用，想着方便大家就放出来了
#### 如何使用
- 打开cherry_update脚本,写上你的代理地址(如果需要的话)，依据自己需要配置其他变量，保存到任意PATH目录（比如/usr/bin），运行
```
chmod +x /path/to/cherry_update
```
之后只需要在终端运行cherry_update即可
- 奥，对了，你可能还需要做一个desktop文件
```
[Desktop Entry]
Categories=Development;
Exec=/opt/cherry/cherry-studio.appimage
Icon=cherry-studio
Name=Cherry Studio
Terminal=false
Type=Application
```
注意：你需要将图标文件cherry-studio.png放到
```
/usr/share/icons/hicolor/48x48/apps/cherry-studio.png
```
为了兼容性，我建议你同时放16x16，32x32，64x64，128x128，256x256下面并缩放到对应大小
当然如果你想省事，也可以直接放到/usr/share/pixmaps/ 然后期待桌面能正确缩放   
