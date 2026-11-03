MIU KESA — LE PRIX DU DESTIN
Projet Android avec génération APK dans le cloud (sans installer Android Studio sur votre PC).

MÉTHODE
1. Décompressez ce ZIP sur votre ordinateur.
2. Créez un compte gratuit sur https://github.com si vous n'en avez pas.
3. Créez un nouveau dépôt (repository) vide sur GitHub.
4. Importez tous les fichiers et dossiers de ce projet dans le dépôt (Add file > Upload files).
5. Ouvrez l'onglet Actions du dépôt.
6. Choisissez « Générer APK MIU KESA », puis « Run workflow ».
7. Quand l'exécution est terminée (vert), ouvrez-la et téléchargez l'artefact « MIU-KESA-APK ».
8. Décompressez l'artefact téléchargé : app-debug.apk est l'application Android de test à transférer sur le téléphone.

IMPORTANT
- Cette méthode compile l'APK dans les serveurs GitHub Actions. Android Studio n'est pas nécessaire sur votre PC.
- Une première compilation peut prendre quelques minutes.
- L'APK debug est destiné aux essais et à l'installation manuelle. La publication Play Store nécessite une version signée (AAB) et un compte développeur Google Play.
- Le projet contient le roman et ses fonctions de lecture. Vérifiez soigneusement le rendu avant toute diffusion publique.
