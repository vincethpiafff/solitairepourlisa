# Solitaire Klondike — application Android

1. Installe Android Studio (gratuit) : https://developer.android.com/studio
2. File > Open, choisis ce dossier « SolitaireAndroid ».
3. Laisse Android Studio synchroniser (il télécharge Gradle et le SDK la première fois).
4. Branche ton téléphone (mode développeur + débogage USB activés) et clique ▶ Run.
   Ou : Build > Build App Bundle(s) / APK(s) > Build APK(s), puis copie l'APK sur le téléphone.

Le jeu est dans app/src/main/assets/index.html : modifie-le pour changer le jeu.
Pour le Play Store : Build > Generate Signed App Bundle.

## Sans Android Studio : compilation par GitHub
1. Crée un dépôt sur github.com et dépose tous les fichiers de ce dossier (Add file > Upload files).
2. Vérifie que le fichier `.github/workflows/build.yml` est bien présent (sinon : Add file > Create new file, nomme-le `.github/workflows/build.yml` et colle son contenu).
3. Onglet Actions : la compilation démarre seule (environ 3 minutes).
4. Ouvre la compilation terminée (coche verte), télécharge « Solitaire-APK » en bas de page, dézippe : tu obtiens Solitaire.apk.
5. Copie Solitaire.apk sur le téléphone, ouvre-le et autorise l'installation.
