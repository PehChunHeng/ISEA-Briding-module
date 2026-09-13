Reflection:
Learnt how to used different file editors like nano and gedit. nano being easier to use as it does not go out of the terminal. Using nslookup to find specific domains and also ip a to see my private ip addresses and using websites like findmyipaddress to see my public address.

Screenshots of what was done for this lab:
<img width="1914" height="1040" alt="Screenshot 2026-09-12 151316" src="https://github.com/user-attachments/assets/e60ce87c-5e33-4ba5-b4a3-e405fad1abb4" />
Set up vmware workstation and ubuntu virtual machine
account details: 
username:admin1@admin 

<img width="695" height="515" alt="image" src="https://github.com/user-attachments/assets/8fbf8028-0c60-4ba7-9a5f-f5f659691566" />
ps-e command (use to show currently running processes)

<img width="654" height="440" alt="image" src="https://github.com/user-attachments/assets/121f5ec2-a9d0-4ff3-a98c-5a91bd04b7fb" />
top command (another command to show running processes)

<img width="669" height="418" alt="image" src="https://github.com/user-attachments/assets/3e71221c-9b14-4869-9a11-be0c70163e75" />
ls and ls -la command (use to list file)


ls only lists the file while ls -la lists all the files with the permission writes and date created

<img width="662" height="419" alt="image" src="https://github.com/user-attachments/assets/3beb5447-2c80-4e55-aeac-c828d044d0fa" />
Using touch testfile and gedit command, had to sudo-apt install gedit command 

<img width="930" height="788" alt="image" src="https://github.com/user-attachments/assets/87c4ca0f-2863-4366-866a-97a0e21d429d" />
wrote "this is a test" using gedit command 

<img width="946" height="785" alt="image" src="https://github.com/user-attachments/assets/8c7a428f-1195-4837-8fc6-fa82bdc0c4a2" />
gedit testfile (to edit created testfile)

<img width="683" height="491" alt="image" src="https://github.com/user-attachments/assets/dd1651b6-df40-4ff7-880f-2b6d695c3e93" />
nano testfile


nano vs gedit 
nano remains on the terminal to edit while gedit will open the file to edit 

<img width="795" height="509" alt="image" src="https://github.com/user-attachments/assets/fcdc92ec-7e05-47c5-a6eb-89925f0efdd6" />
cat vs less command

<img width="718" height="162" alt="image" src="https://github.com/user-attachments/assets/1a452cfd-b6fd-43b9-9f4b-9467e4887ca9" />
cp command (to copy files)

<img width="691" height="143" alt="image" src="https://github.com/user-attachments/assets/f65042a6-5a59-4d90-9af6-0ca79303c821" />
mv command (to move files into another file) 

<img width="651" height="122" alt="image" src="https://github.com/user-attachments/assets/ab38649a-5457-4784-b7c8-3e6c6366efe4" />
uname -a command

<img width="672" height="260" alt="image" src="https://github.com/user-attachments/assets/03aa9b3a-efb4-4ecb-888f-b5ab04f725f9" />
lsb_release -a command

<img width="681" height="376" alt="image" src="https://github.com/user-attachments/assets/32685093-5732-4435-923d-cbd9e5313323" />
hostnamectl command

<img width="682" height="450" alt="image" src="https://github.com/user-attachments/assets/c8a78a39-1699-44e3-ab65-5ca0231d5a00" />
ls -alt (tells you the specific time, minutes and hours)

<img width="780" height="98" alt="image" src="https://github.com/user-attachments/assets/99ec5ebd-48a1-489d-a28d-f1454ea764c7" />
whoami (shows you which acc u using)

<img width="657" height="176" alt="image" src="https://github.com/user-attachments/assets/da3b58ae-ae23-4365-afd2-f4173033fbeb" />
adduser (only root privileges can create user, hence denied access) 

<img width="657" height="176" alt="image" src="https://github.com/user-attachments/assets/228a49c3-8434-452f-8727-26d902737ca7" />
sudo whoami (will show root user as sudo command is used)

<img width="643" height="341" alt="image" src="https://github.com/user-attachments/assets/8077b7a3-38df-4fd8-97e3-5fa3c4053f4a" />
using sudo adduser to create new acc

<img width="695" height="425" alt="image" src="https://github.com/user-attachments/assets/ad6206a2-b05b-4de2-9065-a284ebb17b08" />
ping 8.8.8.8

<img width="642" height="322" alt="image" src="https://github.com/user-attachments/assets/cb0a737e-6c46-4607-a25e-d1841fcb2771" />
showing /etc/hosts contents

<img width="783" height="564" alt="image" src="https://github.com/user-attachments/assets/67dd8141-8c11-4ee5-92ea-8ec10df95707" />
Using nano and editing to make 8.8.8.8 also known as GoogleEpicDNS in /etc/hosts file 

<img width="681" height="322" alt="image" src="https://github.com/user-attachments/assets/0c4bf34f-16d3-4d0a-9805-c8e9a2e86f10" />
able to ping GoogleEpicDNS

<img width="708" height="426" alt="image" src="https://github.com/user-attachments/assets/1746bb2a-54d2-4a3f-92ac-f7fd6cf56a9c" />
nslookup google.com

<img width="698" height="405" alt="image" src="https://github.com/user-attachments/assets/8e4ce269-8e81-4e2e-ac87-57a52998c982" />
installing whois library

<img width="681" height="435" alt="image" src="https://github.com/user-attachments/assets/bc559066-7644-4bbc-82cb-80fbbd040b71" />
whois command executed

<img width="1275" height="591" alt="image" src="https://github.com/user-attachments/assets/3b73528e-9cf7-478b-8c7d-3b6e03f0d3fe" />
<img width="673" height="287" alt="image" src="https://github.com/user-attachments/assets/ff124a87-ef5d-4510-9ba5-4f102fc68a8f" />
Reason why ip a and whatismyipaddress is different is caused one is private ip one is public ip.

