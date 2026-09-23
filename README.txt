APPLICATION ANDROID IMDS — HORS LIGNE

Ce projet transforme le chatbot IMDS en application Android.

L'application :
- fonctionne hors connexion ;
- contient le chatbot directement dans l'application ;
- n'utilise aucune API Internet ;
- conserve l'interface du chatbot ;
- peut être installée sur Android après génération de l'APK.

POUR GENERER L'APK — méthode simple :
1. Ouvrir ce projet dans Android Studio.
2. Attendre que Gradle termine la synchronisation.
3. Choisir Build > Build APK(s).
4. L'APK sera généré dans :
   app/build/outputs/apk/debug/app-debug.apk

Pour une première installation, Android Studio peut avoir besoin d'Internet
pour télécharger les composants de compilation. Une fois l'APK installé,
le chatbot lui-même ne nécessite pas Internet.
