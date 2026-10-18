# Neon Pursuit

Régulateurs contre coureurs, en multijoueur, dans une ville cyberpunk de nuit (vue isométrique).

## Télécharger

👉 **[Télécharger la dernière version (Windows)](https://github.com/Popp-Ranger/neon-pursuit-jeu/releases/latest)** :
dans la page qui s'ouvre, clique sur le fichier `NeonPursuit-….zip` (rubrique *Assets*). Les autres fichiers de la
page servent au lanceur : inutile de les télécharger.

1. Décompresse tout le dossier (garde `NeonPursuit.exe`, `NeonPursuit.pck` et le dossier `jeu` ensemble).
2. Lance `NeonPursuit.exe` : c'est le lanceur. Il regarde s'il existe une nouvelle version, la télécharge si besoin,
   puis lance le jeu. Sans internet, il lance le jeu installé. Tes héros, ta progression et tes options ne sont pas
   touchés.

Tu as une version d'avant la 0.62.0 (sans lanceur) ? Télécharge le zip une dernière fois à la main : ensuite, les mises
à jour arrivent toutes seules.

Windows peut afficher « Windows a protégé votre ordinateur » : le jeu n'est pas signé numériquement (petit jeu fait
maison). Clique sur **Informations complémentaires**, puis **Exécuter quand même**.

## Jouer ensemble

- Un joueur clique sur **HÉBERGER UNE PARTIE** : à la taverne (ou au poste de commandement), son **code
  d'invitation** s'affiche en bas à gauche. Il le copie et l'envoie à ses amis (Discord, SMS…).
- Les amis cliquent sur **REJOINDRE UNE PARTIE**, collent le code et arrivent directement dans le monde.
- Le jeu ouvre tout seul le port **24600 (UDP)** sur la box de l'hôte (UPnP). Si la box refuse, le jeu propose
  d'autres codes : réseau local, ou réseau virtuel gratuit (Radmin VPN, ZeroTier, Tailscale).
- Tout le monde doit avoir la même version : le lanceur s'en charge.
- Le fichier `LISEZMOI.txt` du jeu détaille tout (commandes, règles).

## But du jeu

Le monde est persistant : chacun y entre et en sort quand il veut.

- **Coureurs** : partir de la taverne, sous la ville, sortir par une bouche d'égout, tenir 5 minutes en ville sans se
  faire arrêter, puis s'échapper en redescendant par une bouche (100 points). Hugues, le patron de la taverne, a des
  quêtes ; le tableau des missions, des livraisons.
- **Régulateurs** : repérer les coureurs, les taser, les menotter et les amener à la prison du QG (100 points).

Version de test : ce dépôt ne contient que la page de téléchargement.
