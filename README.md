# Le Registre — Clan Ronce Noir 🌲

Ce dépôt **public** sert uniquement au téléchargement des **installateurs Windows officiels** du Registre du clan Ronce Noir (Shore RP).

**Aucun code source privé, compte membre ou donnée du clan n'est publié ici.**

## Télécharger

Les versions publiées seront disponibles dans la section [Releases](https://github.com/victorhoutain/Registre-Ronce-Noir-Updates/releases).

Une fois la première version disponible :
1. Ouvrir la dernière **Release**.
2. Télécharger `Registre-Ronce-Noir-Setup.exe`.
3. Lancer l'installateur sur Windows et suivre les instructions.
4. Les prochaines mises à jour pourront être proposées directement dans l'application, après confirmation de l'utilisateur.

## État

**Canal préparé — aucune release n'a encore été publiée.** Les installateurs ne sont pas encore téléchargeables depuis ce dépôt.

La publication est pilotée depuis le **dépôt source privé** via le workflow GitHub Actions `Publier une mise à jour Windows`, qui exige une confirmation et un jeton de publication à droits limités stocké en tant que secret GitHub Actions.

## Sécurité

- Ne télécharger les installateurs que depuis les **Releases officielles** de ce dépôt.
- L'application vérifie le nom de l'installateur et son empreinte SHA-256 déclarée par GitHub avant lancement.
- Ce contrôle d'intégrité **ne remplace pas** une signature Authenticode. En l'absence de signature, Windows peut afficher un avertissement.
- Les données locales du Registre et les comptes des joueurs ne sont pas stockés ici.

**Projet de démonstration en cours de développement.**