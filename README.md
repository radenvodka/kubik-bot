# kubik-bot
Kubik-bot untuk para maniak receh

# Cara mendapatkan config (deviceCode,tk,token ... etc)

1. Download Packet Capture 
2. Buka , Lalu Klik TOmbol Play dipacket capturenya 
3. Buka ShareIt, Spin 1x,
4. Buka Packet Capture lg. (contoh : http://prntscr.com/kjo7sb)

# Install XAMPP (WINDOWS) dan PHP7 (MANUAL UNTUK LINUX)

**Windows** : 

```
1. Download Xampp : https://downloadsapachefriends.global.ssl.fastly.net/xampp-files/7.2.1/xampp-win32-7.2.1-0-VC15-installer.exe?from_af=true (PHP7)
2. Install in drive c:/xampp
3. run : "c:/xampp/php/php.exe" kubik.php
```

**LINUX** : 

1. Install PHP7 

**Ubuntu Install PHP7 :** 
```
sudo apt-get purge 'php5*'
sudo add-apt-repository ppa:ondrej/php 
sudo apt-get update
sudo apt-get install php7.1 php7.1-common
sudo apt-get install php7.1-curl php7.1-xml php7.1-zip php7.1-gd php7.1-mysql php7.1-mbstring 
```

**Centos Install PHP7 :** 
```
yum -y remove php*
yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm -y
yum install yum-utils -y
yum install php php-mcrypt php-cli php-gd php-curl php-mysql php-ldap php-zip php-fileinfo
```

run in linux : php kubik.php
