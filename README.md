# Onboarding mesures DIRIS Digiware

Formulaire client (page web autonome) pour cadrer une campagne de mesures Digiware :
informations client/projet, nombre de départs (dynamique, jusqu'à 100), et sélection
des grandeurs à mesurer (mode « modèle » ou « libre »), catalogue dérivé des tables
MODBUS des modules **I-35** (courant) et **U-30** (tension).

## Contenu
- `index.html` — l'application complète (HTML + CSS + JavaScript, aucune dépendance).

## Déploiement
Hébergé via **Cloudflare Pages** connecté à ce dépôt : chaque `git push` sur `main`
redéploie automatiquement le site. Le client reçoit une simple URL `https://` à visiter.

## Retour des réponses
Le client remplit puis clique **Télécharger (.json / .csv)** et renvoie le fichier.
(Option future : collecte automatique via un endpoint de formulaire.)
