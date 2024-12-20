
## Introduction

Installation de Lamp via Ansible

---

## Contenu Principal

### Les applicatifs

1. **Utilisateur**
   - **Description**: Création dun utilisateur stagière.
   
2. **Docker**
   - **Description**: Installation de docker via un playbook.
   
3. **LAMP**
   - **Description**: Installation de Lamp via docker grace à un playbook.


---

## Utilisation

- **Utilisateur** : L'utilisateur est connecté sous le nom de **admin**. Utilisateur qui aura prealablement crée avec les permision superutilisateur **sudo usermod -aG sudo admin** 

- **Droit** : Pour que l'utilisateur "admin" n'ait pas à entrer de mot de passe lorsqu'il utilise sudo, édite le fichier sudoers de manière sécurisée : **sudo visudo** sous la ligne **%sudo   ALL=(ALL:ALL) ALL** ajouter cette ligne **admin ALL=(ALL:ALL) NOPASSWD:ALL**




  
### Informations supplémentaires

- **Utilisateur** : L'utilisateur doit avoir etais crée sur toute les machines.
- **Paquet a installer** : Installer **sudo**, **ssh**, **ansible**.
- **Lamp** : Services de serveur web linux apache mysql php.

---

## Conclusion

C'est dossier sert a installer un lamp garec à ansible & playbook, PS : La configuration est adapter a un enviroment test non pour une production.
