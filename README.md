

## README


## INSTRUCTION

download the package from github https://github.com/gderouineau/server-Installation

transfert the package to your server
 $ scp packageName.zip user@ip:/some/path

go to your package directory :
 $ cd /some/path

download unzip :
 $ apt-get -qqy install unzip

unzip the package :
 $ unzip packageName.zip

go into the directory :
 $ cd packageName

change the right of the package :
 $ sudo chmod -R 770 ../packageName

run the programm :
 $ sudo ./ServerInstall

Answer the questions then it's done.

if you have any problem mail me the complete console log to guillaume.derouineau@gmail.com

## Symfony

to update a symfony project dump, cache clear, and set the right to your project
note: your project root should be located in /srv/www
 $ cd symfony && ./update

