# fatal: [server]: FAILED! => {"changed": false, "msg": "apt cache update failed"}


sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 648ACFD622F3D138
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 0E98404D386FA1D9

https://phoenixnap.com/kb/fix-sub-process-usr-bin-dpkg-returned-error-code-1

sudo apt install apt-transport-https

sudo apt autoremove
sudo apt-get remove linux-image-unsigned-5.4.0-1003-ibm
sudo apt-get remove docker-ce

apt --fix-broken install

### 1 - Отключаем кэш
update_cache: no

### 2 - Обновляем пакеты
apt-get update

### 3 - Прописываем ключи 
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 648ACFD622F3D138
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 0E98404D386FA1D9

### 4 - Перезагружаем
reboot

### 5 - Включаем обновлять кэш
update_cache = yes
