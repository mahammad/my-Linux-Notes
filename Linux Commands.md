###Genel kullanılan komutlar.

* Güncelleştirme
 - `sudo apt-get update`
* Versiyon güncelleştirmesi
 - `sudo apt-get upgrade` 
* Gereksiz dosyaların silinmesi
 - `sudo apt-get autoremove`
 - `sudo apt-get autoclean`
 
| Terminal komutu           | görevi                                 |
| --------------------------|----------------------------------------|
|`man komut`| komut hakkinda bilgilendirme|
|`komut --help`| komut hakkinda bilgilendirme|
|`sudo su`, `sudo -i`|root olmanızı sağlar|
|`pwd`| bulunduğunuz dizini gösterir|
|`ls` 		    |  dizinin dosyalarını listeler|
|`ll` 		    |  dizinin dosyalarını ayrıntıları ile listeler|
|`cd ~/Dizinismi/`| istenen dizine kısa yoldan gider|
|`cd ~/Dizinismi/`| ´~´ işareti aslına ´/home/kullanic/´ dizinine eşit görevdedir.|
|`cd .. `		| bir dizin geri gider|
|`cd ~ ` 		| başlanğıc dizinine gider|
|`clear` 		| terminal alanını temizler|
|`sudo init 0 `	| bilgisayarı kapatır |
|`sudo init 6 `	| bilgisayarı yeniden başlatır |
|`bc`           | basit matematiksel hesaplamalar|
|`cp -rp dosya /dizin/`| dosya kopyalama|
|`mv  dosya /dizin/`| dosya taşıma|
|`rm -r(f)  <dosya>`| dosya silme|
|`top`,`htop`| çalışan uygulamalar, sistem bilgisi|
|`reset`| terminalınızı resetlemenizi sağlar|
| `chmod +x dosya`| dosyalara çalışabilirlik izni verilmesi|
|`nano`, `vi`| terminal text editörleri|
|`df -m`| bilgisayar disk bölümleri hakkında bilgilendirme|
|`free -m`  | ram'in `mb` olarak kullanımı hakkında bilgilendirme|
|`sudo mountall -v` | yönetici olarak tüm diskleri birleştirir|
|`cat dosya´ | dosya içeriğini ekrana yazıyor|
|`mkdir Klasörisim´ | klasör oluşturmak için|

####Bazı programların kurulumu
|Program    |Terminal komutu|
|---------- |-----------------------|
|1.Git 		| `sudo apt-get install git`|
|2.gcc 		|`sudo apt-get install gcc` 
|3.JDK 		| `sudo apt-get install openjdk-7-jdk`|
|4.SSH      |`sudo apt-get install openssh-server`|
|5.VirtualBox | `sudo apt-get install virtualbox`|
|6.Wine     		 	    | `sudo apt-get install wine`|
|7.Yüklü programların  | `dpkg --get-selections` |
|8.Google chrome eror  | `sudo awk '!a[$0]++' /etc/apt/sources.list`|
|9.Performans			 |`sudo apt-get install htop`|
|10.Netbeans 		 | `sudo apt-get install netbeans`|
|11.Sensors | `sudo apt-get install lm-sensors`|
|12.htop | `sudo apt-get install htop`|
|13.Geany| `sudo apt-get install geany `|