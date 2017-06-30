 ## Autoscript VPS created by [Telegram: Si Tony](https://t.me/simuncaibetollah):shipit:
 
###### Operating software
:computer:[Putty.exe for PC(64-bit)](https://the.earth.li/~sgtatham/putty/latest/w64/putty.exe)

:phone:[JuiceSSH for Android](https://play.google.com/store/apps/details?id=com.sonelli.juicessh&hl=en)

# Centos 6.9 64-bit Webmin + EasyMenu
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/Centos-kvm.sh
```
 - kemudian paste nie dan tunggu sehingga selesai
```
 bash Centos-kvm.sh
```

# Debian 7 64-bit Webmin + EasyMenu
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/Debian-kvm.sh
 ```
 - kemudian paste nie dan tunggu sehingga selesai
```
 bash Debian-kvm.sh
 ```

# Ubuntu 14 64-bit Unlimited Pritunl
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/UnlimitedUbuntu.sh
```
 - kemudian paste nie dan tunggu sehingga selesai 
```
 bash UnlimitedUbuntu.sh
```

# Debian 8 64-bit Unlimited Pritunl
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/UnlimitedDebian8.sh
```
 - kemudian paste nie dan tunggu sehingga selesai
```
 bash UnlimitedDebian8.sh
```

# Disable MultiLogin SSH User Debian/Ubuntu
 ```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/Autokick-debian.sh
 ```
 - kemudian paste nie dan tunggu sehingga selesai
 ```
 bash Autokick-debian.sh
 ```

# Disable MultiLogin SSH User CentOs
``` 
 wget https://raw.githubusercontent.com/syahz86/VPS/master/Autokick-centos.sh
 ```
 - kemudian paste nie dan tunggu sehingga selesai
 ```
 bash Autokick-centos.sh
 ```
 
# Speedtest Server
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/speedtest.sh
 ```
 - kemudian paste nie dan tunggu sehingga selesai
 ```
 bash speedtest.sh
 ```

# Custom Debian 7 64-bit Webmin with EasyMenu (Multilogin User)
```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/CustomDebian-kvm.sh
```
 - kemudian paste nie dan tunggu sehingga selesai
```
 bash CustomDebian-kvm.sh
```

# Custom Centos 6.9 64-bit Webmin with EasyMenu (Multilogin User)
```
wget https://raw.githubusercontent.com/syahz86/VPS/master/CustomCentos-kvm.sh
```
- kemudian paste nie dan tunggu sehingga selesai
```
 bash CustomCentos-kvm.sh
```
- Jika ada tambahan package sila accept (yum/y)

# EasyAdd Usernew Centos
```
wget https://raw.githubusercontent.com/syahz86/VPS/master/conf/create-user.sh
cp /root/create-user.sh /usr/bin/usernew
chmod +x /usr/bin/usernew
```
Jalankan command```usernew```untuk add user baru

# User Expired Centos
 ```
 wget https://raw.githubusercontent.com/syahz86/VPS/master/conf/autoexpire.sh && chmod +x autoexpire.sh
 ```
 untuk menggunakannya taip: ```sh autoexpire.sh```
 
 untuk melihat user yang sudah expired taip : ```cat expireduser.txt```
 
 # Cara Mengatasi IP VPS di Blacklist oleh PlayStation Network
 
 - Copy paste je script dan tekan enter
 ```iptables -A OUTPUT -d account.sonyentertainmentnetwork.com -j DROP
iptables -A OUTPUT -d auth.np.ac.playstation.net -j DROP
iptables -A OUTPUT -d auth.api.sonyentertainmentnetwork.com -j DROP
iptables -A OUTPUT -d auth.api.np.ac.playstation.net -j DROP

 
