☘ SUPPORT OS ☘  
  
➽ Debian 10 & 11 (recommended)   
➽ Ubuntu 20.04   

⚡️ INSTALASI ⚡️     

❏ STEP 1 :    
apt-get update && apt-get upgrade -y && apt dist-upgrade -y && update-grub

❏ STEP 2 :    
apt install curl jq wget screen build-essential -y && reboot

❏ STEP 3:    
➽ Pastikan anda sudah login sebagai root :    
apt install tmux -y && wget -q https://raw.githubusercontent.com/rosi606/R051VPN/main/home && chmod +x home && tmux new-session -d -s rosivpn './home' && tmux attach -t rosivpn

❏ STEP 4 :     
➽ If during the installation connection was lost, login to the vps again and run the command ☞shell

tmux attach -t rosivpn
