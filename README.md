# Onboarding mesures DIRIS Digiware

Formulaire client (page web autonome) pour cadrer une campagne de mesures Digiware :
informations client/projet, nombre de départs (dynamique, jusqu'à 100), et sélection
des grandeurs à mesurer (mode « modèle » ou « libre »), catalogue dérivé des tables
MODBUS des modules **I-35** (courant) et **U-30** (tension).

## Contenu
- `index.html` — l'application complète (HTML + CSS + JavaScript, aucune dépendance).

## Déploiement
Hébergé via **GitHub Pages** (branche `main`, racine) :
<https://sevlamitraille.github.io/digiware-onboarding/>
Chaque `git push` sur `main` redéploie automatiquement le site (~1 min). Le client
reçoit une simple URL `https://` à visiter — sécurité entreprise OK (c'est un site web).

## Retour des réponses
Le client remplit puis clique **Télécharger (.json / .csv)** et renvoie le fichier.
(Option future : collecte automatique via un endpoint de formulaire.)
