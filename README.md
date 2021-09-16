# ansible_entretien
Playbook Ansible qui installe et démarre un serveur nginx, sur un système Ubuntu ou Debian. Il crée un utilisateur wordly, et envoie un fichier "hello World" au niveau du home directory.
Ce code ne fonctionne qu'en local. Pour l'exécuter sur une machine distante, il suffit de modifier le fichier host en lui indiquant la bonne adresse ip ainsi que les identifiants ssh de la machine.

#Pré-requis
* Installer ansible

```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
```

##Execution du script
```bash
sudo ansible-playbook playbook.yml 


