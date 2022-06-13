# adb
1. remove miui bloatware
```html
pm uninstall --user 0 com.android.egg
pm uninstall --user 0 com.facebook.appmanager
pm uninstall --user 0 com.facebook.services
pm uninstall --user 0 com.facebook.system
pm uninstall --user 0 com.facebook.katana
pm uninstall --user 0 com.google.android.apps.subscriptions.red
pm uninstall --user 0 com.miui.msa.global
pm uninstall --user 0 com.google.android.apps.googleassistant
pm uninstall --user 0 com.xiaomi.joyose
pm uninstall --user 0 com.miui.notes
pm uninstall --user 0 com.google.android.gms.location.history
pm uninstall --user 0 com.mipay.wallet.id
pm uninstall --user 0 com.mipay.wallet.in
pm uninstall --user 0 com.google.android.youtube
pm uninstall --user 0 com.google.android.googlequicksearchbox
pm uninstall --user 0 com.android.providers.userdictionary
pm uninstall --user 0 com.android.hotwordenrollment.okgoogle
pm uninstall --user 0 com.android.protips
pm uninstall --user 0 com.google.ar.lens
pm uninstall --user 0 com.miui.userguide
pm uninstall --user 0 com.android.chrome
pm uninstall --user 0 com.xiaomi.payment
pm uninstall --user 0 com.hippogames.ludosaga.mi
pm uninstall --user 0 com.block.puzzle.game.hippo.mi
pm uninstall --user 0 com.mi.global.shop
pm uninstall --user 0 in.amazon.mShop.android.shopping
pm uninstall --user 0 com.netflix.mediaclient
pm uninstall --user 0 com.opera.app.news
pm uninstall --user 0 com.opera.branding
pm uninstall --user 0 com.opera.branding.news
pm uninstall --user 0 com.opera.mini.native
pm uninstall --user 0 com.mi.global.bbs
pm uninstall --user 0 com.facebook.katana
pm uninstall --user 0 in.mohalla.brandprovider
pm uninstall --user 0 in.mohalla.sharechat
pm uninstall --user 0 com.duokan.phone.remotecontroller.peel.plugin
pm uninstall --user 0 com.eterno
pm uninstall --user 0 net.one97.paytm
pm uninstall --user 0 com.xiaomi.joyose
pm uninstall --user 0 com.miui.notes
pm uninstall --user 0 com.google.android.feedback
pm uninstall --user 0 com.mi.global.shop
pm uninstall --user 0 in.amazon.mShop.android.shopping
pm uninstall --user 0 com.netflix.mediaclient
pm uninstall --user 0 com.opera.app.news
pm uninstall --user 0 com.opera.branding
pm uninstall --user 0 com.opera.branding.news
pm uninstall --user 0 com.opera.mini.native
pm uninstall --user 0 com.google.android.printservice.recommendation
pm uninstall -k --user 0 com.android.bips
pm uninstall -k --user 0 com.miui.bugreport
pm uninstall -k --user 0 com.miui.fmservice
pm uninstall -k --user 0 com.miui.fm
pm uninstall -k --user 0 com.caf.fmradio
pm uninstall -k --user 0 com.google.android.marvin.talkback
pm uninstall -k --user 0 com.google.android.tts

```
# ubuntu
1. uninstall firefox
```html
sudo apt-get purge firefox
sudo rm -rf .mozilla/firefox
sudo rm -rf .macromedia
sudo rm -rf .adobe
sudo rm -rf /etc/firefox
sudo rm -rf /usr/lib/firefox
sudo rm -rf /usr/lib/firefox-addons
sudo apt update && sudo apt upgrade
sudo apt autoremove
```

2. setup desktop
```html
gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock show-show-apps-button false
gsettings set org.gnome.shell.extensions.desktop-icons show-trash false
gsettings set org.gnome.shell.extensions.desktop-icons show-home false
```
