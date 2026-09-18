# ipaHUB

IPA Hub 🍏

Bienvenue sur IPA Hub, une plateforme web  entièrement automatisée pour le téléchargement direct de fichiers ⁠.ipa⁠ iOS. Conçu avec une interface sombre inspirée des meilleurs hubs de jailbreak et de tweaker, ce site ne nécessite aucune modification de code pour garder vos applications à jour.

✨ Fonctionnalités Clés:

￼ 🔄 Mises à jour automatiques via l'API GitHub : Le site interroge en temps réel les dépôts officiels des développeurs pour récupérer dynamiquement le dernier fichier ⁠.ipa⁠ disponible dans les Releases.

￼ 📝 Visionneuse Markdown Intégrée : Chaque application dispose d'une modale d'information complète affichant les documentations officielles des GitHub (compatibilités, prérequis, crédits, avertissements) converties proprement grâce à ⁠marked.js⁠.

￼ ⚡ Design Glassmorphism Moderne : Interface fluide conçue avec Tailwind CSS, polices Inter, animations fluides et compatibilité mobile totale (responsive design).

￼ 🛡️ Sécurité et Fallback : Si aucun fichier ⁠.ipa⁠ direct n'est trouvé dans les assets de la dernière release, le système redirige automatiquement l'utilisateur vers la page officielle des releases GitHub pour éviter toute impasse.

📱 Applications Référencées: 

Le hub intègre nativement les outils et tweaks essentiels de la communauté :

1. Ketamine (par ⁠nouvborne⁠) : Éditeur MobileGestalt sur l'appareil (iOS 26/27).
2. Airlift (par ⁠0xjohnnydev⁠) : Outil de gestion et transfert avancé.
3. Aircard (par ⁠mak5er⁠) : Manipulation et gestion NFC avancée.
4. 3105 (par ⁠yangjiii⁠) : Suite d'utilitaires et exploits système.
   
🚀 Installation & Utilisation:

Ce site est contenu dans un fichier unique (⁠index.html⁠) pour une simplicité de déploiement maximale.

1. Téléchargez ou copiez le fichier ⁠index.html⁠.

2. Hébergez-le sur n'importe quel hébergeur statique de votre choix :
   
￼ GitHub Pages (Recommandé et gratuit)
￼ Vercel
￼ Netlify
￼ Ou simplement en ouvrant le fichier dans votre navigateur web.

🛠️ Comment ajouter une nouvelle application ?
Pour ajouter ou modifier une application dans le hub, ouvrez le fichier ⁠index.html⁠, repérez le tableau JavaScript ⁠apps⁠ dans la balise ⁠<script>⁠, et ajoutez un objet avec la structure suivante :

{
    id: 'nom-unique',
    name: 'Nom de l\'App',
    author: 'pseudo-github',
    repo: 'nom-du-repo',
    icon: 'fa-cube', // Icône FontAwesome (ex: fa-syringe, fa-terminal...)
    shortDesc: 'Courte description affichée sur la carte.',
    description: `# Titre en Markdown\n\nVotre description détaillée ici...`
}


⚠️ Avertissement / Disclaimer
Ce projet est fourni à des fins éducatives et de recherche. La modification des fichiers système et l'utilisation de tweaks non officiels peuvent comporter des risques (instabilité, boucles de redémarrage). Utilisez toujours ces outils à vos propres risques et veillez à effectuer des sauvegardes régulières de vos appareils.

📜 Licence
Projet open-source distribué sous licence MIT. Les applications tierces référencées restent la propriété exclusive de leurs auteurs respectifs.
