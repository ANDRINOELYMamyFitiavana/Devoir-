# Devoir
telecharger des code source:mysql;apache;php(dernier versiondans le site officiel)
extracter chaque fichier par le commande:tar -xf [nom du code source]
telecharger les commande make et cmake:
```
sudo apt install make
sudo apt install cmake
```
MYSQL
entrer dans le dossier mysql et creer un dossier "build"
par : mkdir build
apres entres dans le nouveau dossier build par : cd build/
```
cmake ..
```
sudo make
```
sudo make install
```
![image final apres la telechargement](https://github.com/ANDRINOELYMamyFitiavana/Devoir/blob/b1f183929ec93232c945f61c6c00a0caf18d68d4/mysql.png)



APACHE
 ```
 cd /usr/local
 ```
 sudo mkdir apache2
 ```
 entrer dans le dossier de l httpd
 ```
 ./configure
 ```
 corriger les erreur aparu
 ```
 sudo apt install libapr3-dev
 ```
 telecharger l'apr ;le prce et l'apr-util(dernier version)
 extraire l'apr et l'apr-util
 ```
 entrer dans l'apr
 cd apr-1.7.4
 ./configure
 ```
 make
 sudo make install
 ```
 entrer dans l'apr-util  et fait comme l'apr et le prce aussi
```
retourne dans le dossier httpd
```
make
```
sudo make install
```
![image final](https://github.com/ANDRINOELYMamyFitiavana/Devoir/blob/main/apache.png)

PHP

entrer dans le dossier de php 
```
./configure
sudo apt install pkg-config
make
makefile
./buildcon
sudo apt-get install libxml-dev
sudo apt-get install libxml2-dev
sudo apt-get install sqlte3
sudo apt-get install libapr3-dev
./configure
make
sudo make install


./confgure
```

