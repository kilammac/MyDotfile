# Pour executer gitUI:

- apres avoir creer la cle ssh avec : `ssh-keygen -t rsa -b 4096 -C "mon_email@gmail.com"- eval $(ssh-agent) && ssh-add ~/.ssh/id_rsa && gitui && eval $(ssh-agent -k)`

- ` eval $(ssh-agent) && ssh-add ~/.ssh/id_ed25519 && gitui && eval $(ssh-agent -k)`
