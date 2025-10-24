📻 WebRadio Player Pro (Lecteur HLS/MP3 Multi-Plateforme)

🌟 Présentation
WebRadio Player Pro est une solution complète de lecteur WebRadio portable, conçue pour offrir une expérience d'écoute optimale sur tous les appareils (PC, tablettes, smartphones).
Développé en HTML, CSS et JavaScript pur, ce projet utilise la puissance de HLS.js pour assurer la compatibilité avec les flux HLS (.m3u8) tout en prenant en charge les flux MP3 traditionnels. L'interface est optimisée pour la navigation tactile grâce à des gestes de swipe (glissement) intuitifs.

Note : Ce projet conserve scrupuleusement les logos et slogans tels que définis par l'utilisateur. En cas d'erreur de chargement d'image (problèmes CORS ou lien brisé), un placeholder minimaliste est affiché pour garantir l'intégrité visuelle de l'interface.

✨ Fonctionnalités Clés
- Compatibilité Universelle : Fonctionne sur PC, iOS et Android.
- Support Multi-Flux : Lecture des streams MP3, AAC, et HLS (.m3u8).
- Interface Responsive et Horizontal : Affichage optimisé pour les grands écrans (PC/Landscape) et une interface réduite pour le mobile.
- Navigation Intuitive par Swipe : Changez de station en glissant le doigt (swipe) sur la pochette principale.
- Gestion des Stations Complète : Ajout, modification, suppression et réorganisation des stations directement depuis les réglages.

Fonctionnalités Avancées :
- Minuterie de Sommeil (Sleep Timer) : Arrêt automatique après une durée définie.
- Thème Personnalisable : Choix de la couleur d'accentuation.
- Import/Export JSON : Sauvegarde et partage faciles de votre liste de stations.
- Robustesse Améliorée : Correction des problèmes de lecture pour les flux nécessitant une politique d'origine stricte (Flux RTP fonctionnels).

💻 Installation & Démarrage
Ce projet est conçu pour être aussi simple que possible à déployer :

1. Téléchargement
Clonez le dépôt ou téléchargez les fichiers :
```bash
git clone https://github.com/votre_utilisateur/WebRadio-Player-Pro.git
cd WebRadio-Player-Pro
```

2. Lancement
Ouvrez le fichier index.html (ou [webradioplayer.html](webradioplayer.html) dans ce workspace) directement dans votre navigateur web.

Conseil : Pour une utilisation professionnelle ou en production, il est recommandé d'héberger ce fichier sur un serveur web (même localement, comme avec l'extension Live Server de VS Code) pour éviter les restrictions de sécurité du navigateur.

⚙️ Configuration des Stations
Les données de stations sont gérées par le Local Storage de votre navigateur.

Gestion Manuelle via l'Interface
- Cliquez sur l'icône ⚙️ (Réglages) en haut à droite.
- Dans la section "Stations", vous pouvez :
  - Utiliser la barre de recherche.
  - Modifier l'ordre des stations (boutons ▲ et ▼).
  - Ajouter une nouvelle station avec son nom, son URL de stream, son logo (optionnel) et son slogan (optionnel).

Importation / Exportation
Pour sauvegarder ou migrer votre liste de stations :
- ⬇️ Exporter : Génère un fichier webradio-pro-export.json contenant toutes vos données.
- ⬆️ Importer : Charge un fichier JSON pour remplacer la liste de stations actuelle.

🕹️ Utilisation du Lecteur
Commandes Principales

Action — Contrôle (Souris/Clavier)
- Lecture / Pause — Bouton ▶ / Espace
- Station Suivante — Bouton ▶ ou → (Flèche droite)
- Station Précédente — Bouton ◀ ou ← (Flèche gauche)
- Mute / Unmute — Bouton 🔇/🔊 ou touche M
- Volume — Slider Volume (PC) ou ↑↓ (Flèches Haut/Bas)

Navigation Mobile
Sur mobile, glissez simplement la pochette pour changer de station :
- Glissement vers la droite : Station Précédente
- Glissement vers la gauche : Station Suivante

🛠️ Technologies Utilisées
- HTML5
- CSS3 (Flexbox et Media Queries pour le Responsive Design)
- JavaScript (ES6+)
- HLS.js : Librairie essentielle pour la gestion des flux HLS complexes.

👤 Auteur
LePeripheriqueGamer