
Le but de ce projet est de reproduire un cercle de culture ("Crop circle" : Un vaste motif ou ensemble de motifs géométriques réalisé dans un champ de céréales). Un script Python a été développé en utilisant une approche orientée objet et en faisant appel aux bibliothèques NumPy et Matplotlib. 

Dans un premier temps, le choix du motif à reproduire ainsi que les objectifs du script ont été définis. Ensuite, les classes de base ("Interval", "Renderable", "Transformation", etc.) ont été implémentées, suivies des classes de fonction ("CoupleSplineFunction", "PolynomialFunction") et des classes de transformations ("Rotation" et "Translation"). Enfin, la classe "Curve" a été conçue pour gérer le rendu des objets "Renderable" avec Matplotlib, ainsi que la logique pour assembler toutes les formes et les dessiner.

Nous avons crée un motif  en implémentant l'interpolation de Lagrange, les splines cubiques et les courbes de Bézier en Python à l'aide des bibliothèques NumPy et Matplotlib. Ce projet met en avant l'utilisation d'algorithmes mathématiques pour la création et la manipulation précise de formes géométriques complexes, tout en exploitant les capacités de visualisation graphique.
