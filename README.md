# Tp-link-T2u-Ac600 with Kali Linux version  6.8.11-amd64
Frist Step : 

Create a File With " Mkdir "

Thene Copy and paste Thouse 3 Link in Your New Created File  Turminal .

wget https://kali.download/kali/pool/main/l/linux/linux-headers-6.8.11-common-rt_6.8.11-1kali2_all.deb
wget https://kali.download/kali/pool/main/l/linux/linux-kbuild-6.8.11_6.8.11-1kali2_amd64.deb
wget https://kali.download/kali/pool/main/l/linux/linux-headers-6.8.11-amd64_6.8.11-1kali2_amd64.deb


Second Step : 
After you Copy and paste thouse and Click Enter. you will get new 3 Drive file Example :

 
 linux-headers-6.8.11-common-rt_6.8.11-1kali2_all.deb
 
 linux-headers-6.8.11-amd64_6.8.11-1kali2_amd64.deb 
 
 linux-kbuild-6.8.11_6.8.11-1kali2_amd64.deb


Third Step : 
Exucute  thouse 3 driver file  one by one in Your Same Terminal Example Commend :

1st :  sudo dpkg -i  linux-headers-6.8.11-common-rt_6.8.11-1kali2_all.deb

2nd :  sudo dpkg -i  linux-kbuild-6.8.11_6.8.11-1kali2_amd64.deb

3th :  sudo dpkg -i  linux-headers-6.8.11-amd64_6.8.11-1kali2_amd64.deb 



Fourth Step : 
if the 3th fle drive showning Eoror like This Exaple : 


error: RPC failed; curl 92 HTTP/2 stream 5 was not closed cleanly: CANCE



Fifth Step : 
Download thouse 2 one by one in your new Created Terminal 


1st : git config --global http.postBuffer 4096M


2nd : git config --global http.postBuffer 1M

Thene you Will see Your Eoror Will be Fixt 


Sixth Step : 
Download bc this Commend Exaplem : 



sudo apt get bc 



Seventh Step :
Download Tp-link T2U Ac 600 Driver Example : 


sudo git clone https://github.com/morrownr/8821au-20210708.git


Eighth Step : 
Go to the new Created file and Select the  Tp-link drive with this Example :

8821au-20210708 

Enter in this file with Cd Commend .

Ninth Step : 
After you will Enter you will find this drive Example : 

install-driver.sh

you have to install this drive then your kali linux will be restart

then you can use your all Mode's












 


