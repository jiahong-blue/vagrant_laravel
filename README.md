
## 1.安裝VirtualBox
https://www.virtualbox.org/

## 2.安裝vagrant
https://www.vagrantup.com/

## 3.設定 environment path variable\
加入path
C:\HashiCorp\Vagrant\bin

## 4.裝laravel/vagrant
(1) 
git clone https://github.com/laravel/homestead.git ~/Homestead
(2)
composer require laravel/homestead --dev


## 5.安裝homestead
(1)
(2)windows下
vendor\\bin\\homestead make

## 6.暫停虛擬機
vargrant suspend

## 7.other
* (1)
Q:
Check your Homestead.yaml file, the path to your private key does not exist.
A:
windows下有裝git需產生ssh公鑰
執行ssh-keygen.exe

* (2)刪除虛擬機
vagrant destroy

* (3)連進虛擬機
vagrant ssh

## 參考
https://learnku.com/docs/laravel/7.x/homestead/7450
https://medium.com/@misscoming/%E5%9C%A8-windows-10-%E5%AE%89%E8%A3%9D-vagrant-%E8%B7%91-ubuntu-9e665eeabd71