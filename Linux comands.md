###Genel kullanılan komutlar.

####Güncelleştirme
		- `sudo apt-get update`
	Versiyon güncelleştirmesi
		- `sudo apt-get upgrade`
	Gereksiz dosyaların silinmesi
		- `sudo apt-get autoremove
		- `sudo apt-get autoclean
`ls` 		    > - dizini listeler
`cd` (dizin)    > - bir dizine gider
`cd .. `		> - bir dizin geri gider
`cd ~ ` 		> - başlanğıc dizinine gider
`clear` 		> - terminal alanını temizler
`sudo init 0 `	> - bilgisayarı kapatır 
`sudo init 6 `	> - bilgisayarı yeniden başlatır 

####Bazı programların kurulumu

1.Git 					* `sudo apt-get install git`
2.gcc 					* `sudo apt-get install gcc` 
3.JDK 					* `sudo apt-get install openjdk-7-jdk`
4.SSH 					* `sudo apt-get install openssh-server`
5.VirtualBox 			* `sudo apt-get install virtualbox`
6.Wine     		 	    * `sudo apt-get install wine`
7.Yüklü programların 	* `dpkg` --get-selections
8.Google chrome eror 	* `sudo awk '!a[$0]++' /etc/apt/sources.list`
9.Performans			* `sudo apt-get install htop`
10.Netbeans 			* `sudo apt-get install netbeans`

11.PHP
	1.mySQL:`sudo apt-get install mysql-client-5.5`
  			`sudo apt-get install mysql-server-5.5`
  	2.XAMPP:`sudo add-apt-repository ppa:upubuntu-com/web`
  			`sudo apt-get update`
 			`sudo apt-get install xampp`
  			`sudo /opt/lampp/lampp start`
12.MySQL
	* `sudo apt-get install mysql-server`
	* `sudo apt-get install mysql-client`
13.Eclipse
	* `sudo apt-get install eclipse-platform`
	* `sudo apt-get install eclipse-jdt`
	* `sudo apt-get install eclipse-cdt`

14.Sensors 
	* `sudo apt-get install lm-sensors`
	> - Bilgisayarın ısılarını terminelden gösteren komut.