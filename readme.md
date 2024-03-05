#Guide d'utilisation de Tailscale
Ce guide explique comment utiliser Tailscale sur Linux, Windows et macOS.

##Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants :

Un compte Tailscale (vous pouvez vous inscrire sur https://tailscale.com)
Un système d'exploitation Linux, Windows ou macOS
##Installation
###Linux
Ouvrez un terminal.
Exécutez la commande suivante pour installer Tailscale :

curl -fsSL https://pkgs.tailscale.com/stable/ubuntu/focal.gpg | sudo apt-key add -
curl -fsSL https://pkgs.tailscale.com/stable/ubuntu/focal.list | sudo tee /etc/apt/sources.list.d/tailscale.list
sudo apt update
sudo apt install tailscale
sudo tailscale up
Suivez les instructions à l'écran pour terminer la configuration.
Info importante
Tailscale doit étre installer dans les deux systemes (client et serveur) pour que la connexion soit établie.

Windows
Téléchargez le programme d'installation de Tailscale à partir de [https://tailscale.com/download].
Exécutez le programme d'installation et suivez les instructions à l'écran pour installer Tailscale.
macOS
Téléchargez le programme d'installation de Tailscale à partir de [https://tailscale.com/download].
Ouvrez le fichier téléchargé et suivez les instructions à l'écran pour installer Tailscale.
Configuration
Une fois Tailscale installé, suivez les étapes ci-dessous pour configurer votre compte :

Ouvrez un terminal ou une invite de commandes.
Exécutez la commande suivante :

tailscale login
Suivez les instructions à l'écran pour vous connecter à votre compte Tailscale.

Utilisation
Maintenant que vous avez installé et configuré Tailscale, vous pouvez l'utiliser pour établir des connexions sécurisées entre vos appareils.

Pour plus d'informations sur l'utilisation de Tailscale, consultez la documentation officielle sur [https://tailscale.com/docs]