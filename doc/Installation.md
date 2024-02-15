# Installation 

## Installation du serveur 

sudo apt install inspircd 
sudo ufw allow 6667/tcp 
udo ufw reload 
 
panneau namecheap  
   CNAME irc portefolio.online. 
   CNAME * portefolio.online. 
 
sudo chmod +x /etc/inspircd/  OU  sudo usermod -aG irc nadine 
sudo ls ou ls 
sudo cp inspircd.conf inspircd.conf.copie 

sudo jed inspircd.conf 
	voir fichier de config dans github 
sudo service inspircd restart 

## Installation du client 

sudo apt install weechat 
	weechat 
	/server add portefolio irc.portefolio.online/6667 
	/connect portefolio 
	/join #cafe 

	/oper operateur testtest 

https://weechat.org/files/doc/stable/weechat_quickstart.en.html 
