IMDS - Construction automatique de l'APK

1. Crée un dépôt GitHub et mets-y tous les fichiers de ce projet.
2. Le workflow .github/workflows/build-apk.yml se lance automatiquement après un push sur main.
3. Sur GitHub : Actions > Construire APK IMDS > ouvre la dernière exécution.
4. Dans Artifacts, télécharge IMDS-APK.
5. Décompresse l'artifact et installe app-debug.apk sur Android.

Le chatbot lui-même ne demande aucune connexion Internet après installation.
