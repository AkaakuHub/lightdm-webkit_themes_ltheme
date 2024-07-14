https://github.com/lveteau/lightdm-webkit-modern-arch-theme

をもとにカスタマイズ


# KDEでスクリーンロックをlightDMのltheme（これ）に上書きする方法
/usr/share/plasma/shells/org.kde.plasma.desktop/contents/lockscreen/LockScreenUi.qmlを開き、
Component.onCompletedを探し、
`sessionManagement.switchUser();`
に書き換える。

## 参考文献
適用方法:
https://qiita.com/Hayao0819/items/7784178c7fd568291905