# PER
apt-get install git apache2 mysql-server ssh phpmyadmin
cd PER
./konfigurasi
vim /etc/bind/named.conf.local
vim /etc/db.192
vim /etc/db.murid
a2dissite default
/etc/init.d/apache2 reload
a2ensite murid.sekolah.sch.id
/etc/init.d/apache2 reload

kalau gini lagi g berhasil udahlah.
