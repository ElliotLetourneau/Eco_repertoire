# 🌿 Éco Répertoire

Un répertoire visuel de marques et produits respectueux de l'environnement, classés par catégorie, avec une barre de recherche intégrée.

## ✨ Fonctionnalités

- **Recherche en temps réel** — filtrez par nom de marque, catégorie ou type de produit
- **Logos automatiques** — chaque marque affiche son logo, avec repli sur les initiales si indisponible
- **Classement par catégorie** — navigation claire et intuitive
- **Liens directs** — cliquez sur une carte pour visiter le site de la marque

## 📂 Catégories

| Catégorie | Description |
|---|---|
| ♻️ Objets environnementaux | Produits du quotidien écoresponsables |
| 🦷 Soins buccaux | Brosses à dent, dentifrices, et plus |
| 🧴 Soins corporels | Déodorants, savons, rasoirs, etc. |
| 👗 Habillement | Vêtements, souliers, accessoires durables |
| 🔄 Mode de seconde main | Plateformes d'achat de vêtements usagés |
| 🍽️ Cuisine | Accessoires et contenants zéro déchet |
| 💻 Technologie | Appareils et solutions tech durables |
| 🥗 Nourriture | Produits alimentaires écoresponsables |
| 🧱 Matériaux de construction | Briques et matériaux alternatifs |
| 🪑 Meubles | Mobilier durable et éthique |
| 🏔️ Sports | Équipements et accessoires de sport verts |
| 🏅 Certifications | Labels et certifications environnementales |

## 🚀 Déploiement sur GitHub Pages

1. Forkez ou clonez ce repo
2. Assurez-vous que `index.html` est à la racine du projet
3. Allez dans **Settings → Pages**
4. Sous *Branch*, sélectionnez `main` et sauvegardez
5. Votre site sera accessible à :

```
https://[votre-username].github.io/[nom-du-repo]
```

## 🛠️ Utilisation locale

Aucune dépendance à installer. Ouvrez simplement `index.html` dans votre navigateur.

```bash
git clone https://github.com/[votre-username]/[nom-du-repo].git
cd [nom-du-repo]
open index.html
```

## ➕ Ajouter une marque

Dans `index.html`, trouvez la catégorie souhaitée dans le tableau `data` et ajoutez un objet :

```js
{ name: "Nom de la marque", url: "https://exemple.com/", tag: "Type de produit" }
```

Le champ `tag` est optionnel — il apparaît en petit sous le nom de la marque.

## 📋 Certifications reconnues

Ce répertoire inclut une section dédiée aux certifications environnementales de référence :

- **B Corporation** — impact social et environnemental vérifié
- **1% for the Planet** — 1 % des ventes reversé à des OSBL environnementaux
- **Fair Trade** — commerce équitable
- **GOTS** — textile biologique certifié
- **OEKO-TEX** — textile sans substances nocives
- **FSC** — gestion forestière responsable
- **Rainforest Alliance** — biodiversité et agriculture durable
- **Écologo / UL** — certification environnementale canadienne
- **Cradle to Cradle** — économie circulaire
- **Climate Neutral** — neutralité carbone vérifiée

---

*Fait avec 💚 pour un mode de vie plus durable*
