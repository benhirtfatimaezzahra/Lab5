# Lab4 – Gestion d'une Classe

Application Python interactive pour gérer une liste d'étudiants avec leurs informations (nom, âge, note). Ce mini-projet permet d'effectuer des opérations CRUD complètes et d'obtenir des statistiques sur la classe.

Le programme illustre les concepts avancés de Python : manipulation de listes, fonctions, boucles, gestion d'erreurs et menu interactif.

---

##  Fonctionnalités

### Gestion des étudiants
- **Afficher** : visualiser tous les étudiants avec numérotation
- **Ajouter** : saisir un nouvel étudiant (nom, âge, note)
- **Supprimer** : retirer un étudiant par son numéro (avec confirmation)
- **Modifier** : mettre à jour les informations d'un étudiant existant
- **Rechercher** : trouver des étudiants par nom (recherche partielle insensible à la casse)

### Statistiques
- Calcul de la moyenne générale de la classe
- Identification de la meilleure note (avec nom de l'étudiant)
- Identification de la moins bonne note (avec nom de l'étudiant)

### Sécurité et Validation
- Validation robuste des entrées utilisateur
- Gestion des erreurs (valeurs invalides, index hors limites)
- Confirmation avant suppression
- Protection contre les champs vides
- Modification sélective (laisser vide pour conserver la valeur)

---

##  Architecture
```
lab5.ipynb → Notebook Jupyter contenant :

1. Données initiales
   - Liste classe avec 3 étudiants pré-enregistrés

2. Fonctions principales
   - afficher_classe() : affichage formaté avec numérotation
   - ajouter_etudiant() : ajout avec validation
   - supprimer_etudiant() : suppression sécurisée avec confirmation
   - mettre_a_jour_etudiant() : modification flexible
   - afficher_statistiques() : calculs statistiques
   - rechercher_par_nom() : recherche intelligente

3. Interface utilisateur
   - Menu interactif avec 7 options
   - Boucle principale avec gestion des choix
   - Option de sortie propre
```

---

##  Installation

Cloner le projet :
```bash
git clone https://github.com/benhirtfatimaezzahra/Lab5.git
```

Ouvrir le notebook avec Jupyter :
```bash
cd Lab5
jupyter notebook Lab5.ipynb
```

Ou utilisez JupyterLab :
```bash
jupyter lab Lab5.ipynb
```

---



##  Notes Techniques

### Concepts Python utilisés
- **Listes imbriquées** : structure de données `[nom, âge, note]`
- **Fonctions modulaires** : séparation des responsabilités
- **`enumerate()`** : numérotation automatique à partir de 1
- **`try/except`** : gestion des erreurs de conversion et d'index
- **`lambda`** : fonctions anonymes pour `min()` et `max()`
- **List comprehension** : `[etudiant[2] for etudiant in classe]`
- **String methods** : `.strip()`, `.lower()` pour normaliser les entrées
- **Boucle infinie** : `while True` avec sortie par `break`

## Démonstration


https://github.com/user-attachments/assets/9c66ff28-7043-467d-a6b3-18e781552f0d



##  Auteur

**Nom :** Benhirt Fatima Ezzahra  
**Cours :** Introduction à Python  
**Date :** Novembre 2025  
**Encadré par :** Pr. Mohamed LACHGAR
