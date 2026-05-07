# 🔷 Jeu de Formes Géométriques

**Étudiante :** Hanane ELFADIL — IRISI 2  
**Enseignant :** Outhman BOURKOUKOU  
**Établissement :** Faculté des Sciences et Techniques — Université Cadi Ayyad, Marrakech

---

## 📌 Description

Application web interactive permettant de générer et manipuler des formes géométriques en **ASCII art**. L'utilisateur peut choisir une forme, configurer ses dimensions, personnaliser le motif de dessin, puis faire pivoter la forme dans quatre directions avec un codage couleur.

---

## ✨ Fonctionnalités

- Choix parmi **3 formes géométriques** : Triangle, Rectangle, Cercle
- Configuration des **dimensions** spécifiques à chaque forme
- Personnalisation du **motif ASCII** (caractère libre)
- Visualisation de la forme générée en **ASCII art**
- **Rotation** dans 4 directions (Haut, Droite, Bas, Gauche) avec codage couleur
- Bouton de **réinitialisation** pour recommencer

---

## 🗂️ Structure du Projet

```
jeu-formes-geometriques/
├── index.html      # Structure HTML de l'application
├── style.css       # Feuille de styles CSS (design & animations)
├── script.js       # Logique JavaScript (génération & rotation)
└── README.md       # Documentation du projet
```

---

## 🛠️ Technologies Utilisées

| Technologie | Rôle |
|-------------|------|
| HTML5 | Structure et contenu de l'application |
| CSS3 | Design, mise en page et animations |
| JavaScript | Logique métier et interactivité |

---

## 🚀 Lancement

Aucune installation requise. Il suffit d'ouvrir le fichier `index.html` dans un navigateur web moderne.

```bash
# Cloner le dépôt (si applicable)
git clone <url-du-depot>

# Ouvrir dans le navigateur
open index.html
```

---

## 🎮 Utilisation

1. **Choisir une forme** en cliquant sur l'un des trois boutons (Triangle, Rectangle, Cercle)
2. **Configurer les paramètres** :
   - Triangle → Base + Motif
   - Rectangle → Largeur + Longueur + Motif
   - Cercle → Rayon + Motif
3. Cliquer sur **Créer** pour générer la forme
4. Utiliser les boutons directionnels pour **faire pivoter** la forme
5. Cliquer sur **Nouvelle Forme** pour réinitialiser

---

## 📐 Logique de Génération

### Triangle
Génère un triangle isocèle en ASCII, ligne par ligne, avec des espaces pour centrer.

### Rectangle
Répète le motif sur `largeur` colonnes × `longueur` lignes.

### Cercle
Utilise la distance euclidienne depuis le centre pour déterminer si chaque case appartient au disque.

---

## 🎨 Aperçu

L'interface présente un fond dégradé rose-pêche, des boutons arrondis avec effets de survol, et une zone d'affichage en police monospace pour un rendu ASCII fidèle.

---

## 📄 Licence

Projet académique — Faculté des Sciences et Techniques de Marrakech, 2024/2025.