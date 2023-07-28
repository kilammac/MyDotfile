# Pour executer gitUI:

-apres avoir creer la cle ssh avec : ssh-keygen -t rsa -b 4096 -C "mon_email@gmail.com"

 -ssh-keygen -t rsa -b 4096 -C "malekmanso@gmail.com"eeval $(ssh-agent) && ssh-add ~/.ssh/id_rsa && gitui && eval $(ssh-agent -k)
