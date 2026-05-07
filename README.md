# 🔷 Jeu de Formes Géométriques



---

##  Description

Application web interactive permettant de générer et manipuler des formes géométriques en **ASCII art**. L'utilisateur peut choisir une forme, configurer ses dimensions, personnaliser le motif de dessin, puis faire pivoter la forme dans quatre directions avec un codage couleur.

---

##  Fonctionnalités

- Choix parmi **3 formes géométriques** : Triangle, Rectangle, Cercle
- Configuration des **dimensions** spécifiques à chaque forme
- Personnalisation du **motif ASCII** (caractère libre)
- Visualisation de la forme générée en **ASCII art**
- **Rotation** dans 4 directions (Haut, Droite, Bas, Gauche) avec codage couleur
- Bouton de **réinitialisation** pour recommencer

---





##  Technologies Utilisées

| Technologie | Rôle |
|-------------|------|
| HTML5 | Structure et contenu de l'application |
| CSS3 | Design, mise en page et animations |
| JavaScript | Logique métier et interactivité |


---



##  Logique de Génération

### Triangle
Génère un triangle isocèle en ASCII, ligne par ligne, avec des espaces pour centrer.

### Rectangle
Répète le motif sur `largeur` colonnes × `longueur` lignes.

### Cercle
Utilise la distance euclidienne depuis le centre pour déterminer si chaque case appartient au disque.

---

##  Aperçu

L'interface présente un fond dégradé rose-pêche, des boutons arrondis avec effets de survol, et une zone d'affichage en police monospace pour un rendu ASCII fidèle.

---

##  Licence

Projet académique — Faculté des Sciences et Techniques de Marrakech, 2024/2025.
