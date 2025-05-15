# Détection de Contours avec Sobel, Canny et Filtrage Gaussien 🧠🖼️

## Résumé du projet

Ce projet a pour objectif de comparer trois techniques classiques de traitement d’image appliquées à la détection de contours :
- Le **filtrage gaussien**, pour le lissage et la réduction du bruit,
- Le **filtre de Sobel**, pour l'estimation des gradients,
- Le **détecteur de Canny**, pour une détection fine et robuste des bords.

Ce notebook Python a été conçu pour être exécuté sous Python 3.9 dans un environnement compatible avec OpenCV (`cv2`) et Matplotlib.

## Contenu du projet

🔹 **Chargement de l’image d’origine**  
🔹 **Application d’un flou gaussien**  
🔹 **Détection des contours avec Sobel**  
🔹 **Détection des contours avec Canny**  
🔹 **Visualisation des résultats et commentaires**  
🔹 **Conclusion générale sur la performance des méthodes**

## Dépendances

Ce projet nécessite les bibliothèques suivantes :

```bash
pip install opencv-python matplotlib numpy
```

## Exécution

1. Clonez le dépôt :
```bash
(https://github.com/LEDOUXKEN/Detection-Contours-Image/new/main?filename=README.md)
```

2. Ouvrez le fichier dans Jupyter Notebook ou VSCode :
```bash
jupyter notebook detection.ipynb
```

## Résultat attendu

Les différentes techniques permettent de mettre en évidence les contours de l’image d’origine avec des approches variées :
- Sobel pour une détection directionnelle (horizontal/vertical),
- Canny pour une détection optimisée,
- Gaussien comme prétraitement essentiel pour lisser l’image.

## Auteur

**Fidèle Ledoux** – Étudiant en Data Science & Intelligence Artificielle  
 [www.linkedin.com/in/ledoux-kenfack-094214334]  
 Basé au Cameroun

## Licence

Ce projet est open-source, distribué sous la licence MIT.

---

> *"L’image est un langage universel, et l’analyse d’images est un pont entre données et vision humaine."*
