# Documentation IT

[Retour à la page d'accueil](../index.md)

## Configuration réseau
- Adresse IP statique : 192.168.1.100
- Masque de sous-réseau : 255.255.255.0
- Passerelle par défaut : 192.168.1.1
- Serveur DNS : 8.8.8.8

## Configuration du serveur web
1. Installez Apache en utilisant la commande : `sudo apt-get install apache2`.
2. Placez vos fichiers HTML dans le répertoire `/var/www/html`.
3. Démarrez le service Apache en utilisant la commande : `sudo systemctl start apache2`.
4. Vérifiez que le serveur web fonctionne en accédant à http://192.168.1.100 depuis un navigateur.
