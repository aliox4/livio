# Livio Baldelli — version logo original, rouge et noir

## Mise en ligne GitHub / Vercel
1. Décompressez le ZIP sur votre ordinateur.
2. Dans votre dépôt GitHub : Add file > Upload files.
3. Déposez TOUS les fichiers et dossiers décompressés à la racine du dépôt. Ne déposez pas le ZIP lui-même ni un dossier parent supplémentaire.
4. Vérifiez que index.html, vercel.json, assets/, page/ et contact/ apparaissent à la racine.
5. Dans Vercel, importez le dépôt. Framework Preset : Other. Root Directory : ./ . Aucun build ni installation nécessaires. Output Directory : . (un point), si ce réglage est demandé.

Le site est statique : pas de dépendances, pas de clé secrète, pas de serveur à configurer. Les fichiers HTML, CSS et JavaScript sont directement modifiables. Les chemins HTML historiques sont conservés.

## Important avant la bascule du domaine
- Le bouton de collecte renvoie actuellement vers https://www.luthier-domicile.fr/nos-tarifs.html, le service de réservation et paiement existant. Cette refonte ne contient pas son backend. Si vous remplacez le site sur ce même domaine, hébergez auparavant l'ancien moteur sur une URL dédiée, puis actualisez le lien dans contact/contactez-nous.html. Sinon le bouton renverra vers la nouvelle grille de tarifs sans prise de rendez-vous.
- Le formulaire de contact ouvre un brouillon dans la messagerie du visiteur. Il n'envoie pas de message automatiquement.
- Les balises SEO utilisent actuellement le domaine de prévisualisation https://livio-baldelli-luthier.divine-swan-0607.chatgpt.site. Remplacez cette origine dans les cinq HTML, sitemap.xml et robots.txt par le domaine définitif lors de la mise en production.
- Les mentions légales restent à compléter avec les informations juridiques validées du professionnel et de l'hébergeur.
- Confirmer la grille tarifaire 2026 et conserver/rediriger les anciennes URL d'actualités lors de la migration.

## Contenu
5 pages, logo officiel et mascotte d'origine, photographies locales WebP, tarifs filtrables, version mobile, métadonnées SEO et données structurées LocalBusiness. Aucun tracker ajouté. Polices Google Fonts avec repli système.
