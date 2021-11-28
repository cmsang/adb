# adb

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

# ubuntu

sudo apt-get purge firefox
sudo rm -rf .mozilla/firefox
sudo rm -rf .macromedia
sudo rm -rf .adobe
sudo rm -rf /etc/firefox
sudo rm -rf /usr/lib/firefox
sudo rm -rf /usr/lib/firefox-addons


sudo apt update && sudo apt upgrade
sudo apt autoremove
gsettings set org.gnome.shell.extensions.dash-to-dock extend-height false
gsettings set org.gnome.shell.extensions.dash-to-dock show-show-apps-button false
gsettings set org.gnome.shell.extensions.desktop-icons show-trash false
gsettings set org.gnome.shell.extensions.desktop-icons show-home false
