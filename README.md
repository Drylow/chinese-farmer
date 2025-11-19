# 📖 The Chinese Farmer's Story - Projet HTML/CSS

Ce projet est la réalisation d'un article en ligne basé sur la célèbre parabole du fermier chinois, souvent attribuée à Alan Watts. Il a été conçu comme un exercice pour maîtriser les fondamentaux de la mise en page web en utilisant le HTML sémantique et le CSS.

---

## ✨ Fonctionnalités et Techniques Utilisées

Ce site présente une implémentation soignée des concepts CSS de base et avancés :

* **HTML Sémantique :** Utilisation des balises <header>, <blockquote>, <figure>, <table>, <footer>, etc., pour structurer clairement le contenu.
* **Thème Sombre (`Dark Mode`) :** Un schéma de couleurs sombre a été appliqué pour un affichage élégant et agréable à l'œil.
* **Typographie :** Utilisation de la police Open Sans importée via Google Fonts.
* **Mise en Page Flottante (`float`) :** Les images des figures sont alignées à l'aide de la propriété float: left;.
* **Nettoyage du Flux (`clear`):** La propriété clear: both; est utilisée sur les titres (<h2>) pour garantir que les sections de l'histoire reprennent le flux normal sous les images flottantes.
* **Listes Personnalisées :**
    * Les puces de la liste sont remplacées par des images de fond (background-image).
    * Le dernier élément utilise un **pseudo-élément (`::before`)** avec un caractère Unicode (❌) pour simuler l'alignement des icônes.
* **Positionnement Fixe :** Un bloc de notification (div.notification) est positionné de manière fixe dans le coin inférieur droit de l'écran (position: fixed;).
* **Améliorations Esthétiques :** Ajout d'ombres portées (box-shadow), de transitions (transition), et d'effets de survol (:hover) pour une meilleure expérience utilisateur.

---

## 🚀 Installation et Lancement

Ce projet ne nécessite aucun environnement de développement complexe.

1. **Cloner le dépôt :**
    ```bash
    git clone [URL_DE_VOTRE_DEPOT]
    ```
2. **Ouvrir le fichier :**
    * Naviguez jusqu'au dossier du projet.
    * Ouvrez le fichier index.html directement dans votre navigateur web (Chrome, Firefox, etc.).

---

## 📁 Structure du Projet
```bash
.
├── index.html         # Le fichier principal de la page web
├── style.css          # Toutes les règles de style (Thème Sombre, mise en page, animations)
└── assets/            # Dossier pour les ressources médias
    ├── bien.png       # Icône pouce levé
    ├── mal.png        # Icône pouce baissé
    ├── chat.png       # Icône chat pour la liste
    └── [Autres images]  # Images utilisées pour l'article (fermier, mars rock, etc.)
```

---

## 🎨 Design et Style

| Élément | Couleur / Style |
| :--- | :--- |
| **Arrière-plan (`body`)** | Gris très foncé (`#1A1A1A`) |
| **Texte principal** | Gris clair (`#E0E0E0`) |
| **Mots-clés `.good`** | Vert vif (`#4CAF50`) |
| **Mots-clés `.bad`** | Rose framboise (`#E91E63`) |
| **Sous-titres (`h2`)** | Jaune Or / Ambre (`#FFC107`) (Basé sur le dernier changement) |
| **Citations (`blockquote`)** | Gris foncé légèrement plus clair (`#252525`) avec bordure firebrick |
| **Images** | Coins arrondis et effet de "saut" au survol. |

    
---

## 👤 Auteur

**Drylow**

* *Projet réalisé dans le cadre d'un cours de développement web sur les bases HTML et CSS.*

---
