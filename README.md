# File-Organizer-Pro
Salut tout le monde ! A l'aide de Claude, j'ai pu faire un organisateur de fichier optimisé avec l'IA. Je trouvais ça sympa de le partager pour ceux que ca intéresserait.

Ce programme est une application desktop en Python qui :
1. Scanne un dossier
2. Classe les fichiers par catégories
3. Détecte les doublons (via hash MD5)
4. Propose des renommages via OpenAI
5. Déplace et renomme les fichiers automatiquement
6. Permet d’annuler la dernière opération

C’est un outil d’organisation orienté production 3D.
Les fichiers sont classés selon leur extension. (.blend, .fbx, .pdf,...)

Comment l’exécuter ?

Version requise : Python 3.10+ 
https://www.python.org/downloads/ → Coche ☑ Add Python to PATH

1. Clique droit sur ton Bureau
2. Nouveau → Document texte
3. Renomme-le : file_organizer_pro.py
4. Clique droit sur le fichier
5. Ouvrir avec → Bloc-notes
6. Colle tout le code
7. Sauvegarde et ferme
8. Clique droit dans le dossier où est ton fichier
9. Ouvrir avec Python ou dans le terminal

Mettre ta clé OpenAI (optionnel)

Si tu veux les suggestions IA :
- Va sur https://platform.openai.com
- Crée une clé API
- Colle-la dans l’application
- Clique Sauvegarder
