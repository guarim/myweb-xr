# myweb-xr
application WebXR de réalité augmentée avec les fonctionnalités suivantes :
Caractéristiques principales :
🎯 Détection d'images : Utilise une image comme marqueur pour déclencher la réalité augmentée
📦 Types de contenu supportés :

Images (JPG, PNG)
Vidéos (MP4, WebM)
Modèles 3D GLB (placeholder cube pour cette démo)

📁 Structure des fichiers :
/assets/
  ├── marker.jpg        (votre image marqueur)
  ├── marker.jpg.mind   (fichier compilé du marqueur - voir ci-dessous)
  ├── content.jpg       (contenu à afficher)
  ├── video.mp4         (ou vidéo)
  └── model.glb         (ou modèle 3D)
Pour utiliser l'application :

Préparer l'image marqueur : Vous devez d'abord compiler votre image marqueur avec l'outil MindAR. Visitez https://hiukim.github.io/mind-ar-js-doc/tools/compile pour créer le fichier .mind
Configurer : Entrez les noms des fichiers (sans "assets/")
Démarrer : Cliquez sur "Démarrer AR" et autorisez l'accès caméra
Scanner : Pointez la caméra vers votre image marqueur


🆕 Nouvelles fonctionnalités :
🎮 Contrôles interactifs :

Rotation :

🖱️ Souris : Clic droit + déplacer
📱 Tactile : Glisser avec 1 doigt


Zoom (échelle) :

🖱️ Souris : Molette de la souris
📱 Tactile : Pincer avec 2 doigts



📍 Support de plusieurs marqueurs :

Ajoutez autant de marqueurs que nécessaire avec le bouton "➕ Ajouter un marqueur"
Chaque marqueur peut avoir :

Son propre fichier image de détection
Son propre contenu (image/vidéo/3D)
Son échelle initiale personnalisée


Suppression individuelle possible

🔘 Menu de navigation (côté droit) :
Trois boutons stylisés qui redirigent vers :

⚙️ Mécanique → mecanique.html
⚡ Électrique → electrique.html
🔧 Maintenance → maintenance.html

💡 Améliorations supplémentaires :

Interface plus moderne avec dégradés de couleurs
Indicateur de contrôles en haut pendant l'AR
Bouton "Config" pour afficher/masquer la configuration pendant l'AR
Animations fluides sur les boutons
