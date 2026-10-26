# Mimo
Projet Mimo : mon linktree 🔗

Ce projet consiste en une page web personnelle de type **Linktree**, conçue pour centraliser mes liens professionnels et mes profils de réseaux réseaux sociaux (LinkedIn et GitHub). 

La page adopte une mise en page moderne, minimaliste et entièrement centrée pour une consultation optimale sur ordinateur comme sur smartphone.

---

## 🎨 Aperçu et fonctionnalités

* **Carte de profil visuelle :** affichage d'une photo de profil arrondie avec une bordure stylisée.
* **Présentation synthétique :** titre ("Julie Gérard"), sous-titre de poste (*Aspiring Web Mobile & Web Developer*) et message d'accueil.
* **Boutons interactifs (style linktree) :**
  * liens vers **LinkedIn** et **GitHub** présentés sous forme de capsules/boutons.
  * effets visuels d'interaction au survol (*hover*, élévation et accentuation de l'ombre).
  * ouverture sécurisée des liens dans un nouvel onglet (`target="_blank"` et `rel="noopener noreferrer"`).

---

## 🛠️ Technologies utilisées

* **HTML5 :** balisage sémantique et intégration de la balise `<meta name="viewport">` pour le responsive design.
* **CSS3 :**
  * alignement et centrage vertical/horizontal via **Flexbox** (`justify-content: center`, `align-items: center`).
  * stylisation moderne avec des arrondis (`border-radius: 50%`, `border-radius: 30px`).
  * animations fluides grâce aux propriétés `transition` et `transform`.

---

## 📂 Structure des Fichiers

```text
.
├── index_3.html        # Structure HTML de la page de liens
├── style_3.css         # Feuille de style CSS
└── img/                # Dossier d'images
    └── ordinateur-portable-pres-de-cactus.jpg  # Photo de profil
