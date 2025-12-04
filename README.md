# Projet : Hôpital Psychiatrique VR (Psy Horror)

## Objectif du Projet

Ce projet est un jeu d'évasion (Escape Game) à l'ambiance horrifique et psychologique, développé pour la **réalité virtuelle (VR)**. Le joueur doit explorer un hôpital psychiatrique abandonné et résoudre des énigmes pour s'échapper.

---

## État Actuel & Fonctionnalités Implémentées

Le projet est en phase de finission technique, se concentrant sur les mécaniques VR et l'ambiance visuelle.

### Fonctionnalités Clés

* **Mouvement & Interaction VR :** Utilisation du **XR Interaction Toolkit** pour le déplacement et la manipulation d'objets.
* **Système d'Énigme**
* **Ambiance Lumineuse :** Contrôle total sur l'éclairage de la scène (noir complet), permettant l'effet de lampe torche dramatique.
* **Effets Visuels :** Brouillard ambiant (système de particules) (abandonnée).
* **Audio (Prototypé) :**
    * Ambiance globale (2D) en boucle.
    * Sons de *grab/drop* pour les objets interactifs.
    ...

---

## Configuration Technique & Lancement

| Configuration | Détail |
| :--- | :--- |
| **Moteur** | Unity (6000.2.10f1) |
| **Pipeline de rendu** | Universal Render Pipeline (URP) |
| **Outil VR** | Unity XR Interaction Toolkit |
| **Langage** | C# |
| **Dépôt principal** | `Assets/Scenes/MainScene.unity` |

### Lancement Rapide

1.  **Cloner le dépôt :** Assurez-vous d'avoir Git et Git LFS configurés.
    ```bash
    git clone [https://www.wordreference.com/fren/d%C3%A9p%C3%B4t](https://www.wordreference.com/fren/d%C3%A9p%C3%B4t)
    ```
2.  **Ouvrir dans Unity :** Ouvrez le dossier racine dans Unity Hub.
3.  **Packages :** Unity devrait automatiquement résoudre les dépendances et importer les assets.
4.  **Lancer :** Lancez la scène `MainScene` via votre casque VR.

---

## Feuille de Route (Prochaines Étapes)

Ces tâches représentent les prochains objectifs majeurs :

### Améliorations Immédiates (Scripts)
* [ ] **...:** ...

### Design & Environnement
* [ ] **Post-Processing :** Finaliser les réglages de Volume Global pour renforcer l'atmosphère d'horreur (Vignette, Color Grading, film grain).
* [ ] **Détails de la Scène :** Utiliser les **Decals** (saleté, sang, graffiti) pour un look "abandonné" sur les murs et sols.
* [ ] **Prochain Puzzle :** Concevoir et implémenter le prochain défi de la zone (ex: Puzzle d'Horloge, Séquence de boutons, etc.).

---

## 🤝 Contribution et Support

Ce projet est conçu comme une base évolutive. Toute suggestion d'amélioration est la bienvenue. N'hésitez pas à ouvrir une *Issue* sur GitHub pour signaler des bugs ou proposer de nouvelles idées de *features*.
