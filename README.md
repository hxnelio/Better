# Better Protect

Better Protect est un bot Discord de protection conçu pour sécuriser les serveurs contre les raids, le spam et les comportements abusifs.

---

## Description

Le bot inclut :

- Protection anti-raid
- Anti-spam
- Système de logs
- Configuration centralisée via fichier `config.js`
- Permissions administrateur
- Système de support

Projet distribué à des fins éducatives.

---

## Prérequis

Avant installation :

- Node.js (v18 ou supérieur recommandé)
- Un bot créé sur le Discord Developer Portal
- Les permissions administrateur sur votre serveur

---

## Installation

Clonez le dépôt :

```bash
git clone https://github.com/hxnelio/Better.git
cd Better
npm install

```js
module.exports = {
    token: "VOTRE_TOKEN_ICI",
    ownerId: "VOTRE_ID_DISCORD",
    supportServeur: "LIEN_DU_SERVEUR_SUPPORT"
}
```

# Lancement
```
node .
node index.js
```

# Crédits

Ce projet est basé en partie sur le travail de
https://github.com/Ruwin-dsc/Better-Protect-Remade

Merci à Ruwin pour la base initiale.
