# Unix_1 - Installation Gitea

## Étapes réalisées

### 1. Préparation du serveur
- Mise à jour du système : `sudo apt update && sudo apt upgrade`
- Installation de git et wget

### 2. Création utilisateur dédié
- Groupe gitea créé
- Utilisateur système gitea créé (uid=997)

### 3. Installation Gitea 1.21.4
- Téléchargement depuis dl.gitea.com
- Binaire placé dans /usr/local/bin/

### 4. Service systemd
- Service créé et activé
- Gitea tourne sur le port 3000
- Status : active (running)

## Commandes clés
```bash
sudo systemctl status gitea
gitea --version
```
