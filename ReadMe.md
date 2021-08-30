# Need more update

# About

Bijoy 52 is a popular Bengali keyboard software. This repository contains the Linux compatible version of Bijoy 52!


# Install

## Ubuntu/Debian Based Distros

- Install Ibus: 
```bash
sudo apt-get install ibus-m17n
```

- Then run this commands:
```bash
sudo chmod 777 /usr/share/m17n/   
```
```bash
sudo chmod 777 /usr/share/m17n/icons
```

## Arch Based Distros
- Install Ibus: 
```bash
pamac install ibus ibus-m17n
```


- Clone this repository 

```bash
git clone https://github.com/rafidalhaque/bijoy_linux.git
```

- Enter into ```bijoy_linux``` directory:

```
cd bijoy_linux/bijoy_linux
```

- Now move this files to ```/usr/share/m17n/icons```

* bn-bijoyClassic.png
* bn-bijoyUnicode.png

Now open extract file and select (2) .png file and move it to: file system>usr>share>m17n>icons> there.
Now Select (2) .mim file and move it to: file system>usr>share>m17n> there.

############Now go to tarminal and copy paste this two code:

sudo chmod 777 /var/lib/dpkg/info/m17n-db.list

gedit /var/lib/dpkg/info/m17n-db.list     

################ Now open (m.17n-db.list) file to: system>var>lib>dpkg>info>m17n-db.list and copy below command and save the file.

/usr/share/m17n/icons/bn-bijoyClassic.png
/usr/share/m17n/bn-bijoyClassic.mim
/usr/share/m17n/icons/bn-bijoyUnicode.png
/usr/share/m17n/bn-bijoyUnicode.mim

 
##########################################################
Don't forget to subscribe our channel youtube.com/techtd
also share it with your family and friends.
Thank you !!!!!!!!!
