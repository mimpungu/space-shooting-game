# space-shooting-game
# Jeu de Tir Spatial

Bienvenue dans ce jeu de tir spatial créé en HTML5, CSS3 et JavaScript. Le but est de piloter votre vaisseau spatial, détruire les ennemis envahisseurs et atteindre le plus haut score possible. Ce jeu est accessible directement dans un navigateur web moderne sans installation nécessaire.

---

## Fonctionnalités

- **Contrôlez votre vaisseau** horizontalement avec les flèches gauche/droite ou les touches A/D.
- **Tirez des projectiles** avec la barre d'espace pour détruire les ennemis.
- **Plusieurs niveaux de difficulté** : Facile, Intermédiaire (par défaut), Difficile.
- **Choix du prénom du joueur** avant de commencer la partie.
- **Système de vies** : vous avez 3 vies avant la fin de la partie.
- **Système de niveaux** : Chaque niveau augmente la vitesse et le nombre d’ennemis.
- **Animations visuelles** : effet d’explosion lors de la destruction d’un ennemi, animation d’entrée du vaisseau.
- **Musique et effets sonores** activables/désactivables avec un bouton Son.
- **Contrôle de pause** via la touche `P` ou un bouton dédié avec indication visuelle.
- **Bouton Quitter** pour retourner à l’écran de démarrage.
- **Guide des commandes** accessible via un bouton info.
- **Design moderne** avec animations et effets lumineux.

---

## Comment jouer

1. Ouvrez le fichier `space-shooting-game.html` dans un navigateur moderne (Chrome, Firefox, Edge, Safari).
2. Sur l’écran d’accueil, entrez votre prénom.
3. Choisissez la difficulté désirée (Facile, Intermédiaire, Difficile).
4. Cliquez sur **Jouer** pour lancer la partie.
5. Déplacez votre vaisseau à gauche et à droite.
6. Appuyez sur la barre d’espace pour tirer.
7. Les ennemis descendent progressivement, détruisez-les avant qu’ils n’atteignent votre niveau.
8. Vous disposez de 3 vies, perdez-les toutes et la partie est terminée.
9. Passez les niveaux pour augmenter la difficulté.
10. Utilisez le bouton **Pause**, la touche `P`, le bouton **Son** pour activer/désactiver les sons ou le bouton **Quitter** pour revenir à l’écran d’accueil.
11. Le bouton **?** affiche les commandes disponibles.

---

## Commandes

- 🔹 **Déplacements** : flèches gauche/droite ou touches `A`/`D`  
- 🔹 **Tir** : barre d’espace  
- 🔹 **Pause** : touche `P` ou bouton Pause  
- 🔹 **Activer/Désactiver son** : bouton Son  
- 🔹 **Quitter jeu** : bouton Quitter  
- 🔹 **Afficher commandes** : bouton `?`

---

## Technologies utilisées

- HTML5  
- CSS3 avec animations  
- JavaScript moderne (ES6+)  
- Canvas API pour le rendu graphique  
- Web Audio API pour les sons et effets sonores  

---

## Accessibilité

- Utilisation d’attributs ARIA pour améliorer l’accessibilité des éléments interactifs.  
- Les changements d’état importants (pause, fin de partie) sont annoncés via des régions ARIA live.  
- Les boutons ont des labels et titres explicites.

---

## Personnalisation et extension

Le code est commenté et organisé pour faciliter les modifications :

- Modifiez les paramètres dans la section JavaScript pour ajuster la vitesse, la taille des ennemis, le nombre de vies, etc.
- Ajoutez des niveaux supplémentaires ou de nouveaux types d’ennemis.
- Intégrez un système de sauvegarde local (localStorage) pour conserver le meilleur score.
- Ajoutez des musiques ou effets sonores avancés.
- Améliorez les graphismes avec des images ou sprites.

---

## License

Ce projet est libre d’utilisation et modifiable sous la licence MIT. Vous pouvez donc le réutiliser, le copier ou le modifier à votre guise.

Merci beaucoup d’avoir choisi ce jeu de tir spatial ! Amusez-vous bien et bon tir !

