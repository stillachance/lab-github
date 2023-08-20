# Laboratoire GitHub

Pour compléter cette étape du laboratoire:

1. À droite du titre *lab-github* de ce dépôt, vous trouverez plusieurs boutons, dont un `Fork`. Cliquez sur ce bouton, puis suivez les étapes affichées pour créer un `fork` de ce dépôt, c'est-à-dire une copie du dépôt sur votre propre compte GitHub.
2. Clonez votre *fork* sur votre poste de travail.
3. Sur votre dépôt Git local, créez une nouvelle branche appelée `ajouter-fonction`.
4. Déplacez-vous sur cette branche.
5. Ouvrez le projet Visual Studio contenu dans le dépôt à l'aide du fichier `.sln`.
6. À l'aide de Visual Studio, ajoutez les fichiers `fonctions.h` et `fonctions.cpp` au projet.
7. Dans ces nouveaux fichiers, créez une fonction `void helloWorld()` qui affiche "Hello World!" à l'écran.
8. Appelez cette fonction dans le `main` à la place du code actuel.
9. Créez un nouveau commit contenant toutes vos modifications. Ce commit doit également inclure les modifications effectuées par Visual Studio aux fichiers `.vcxproj` et `.vcxproj.filters`, autrement vos fichiers `fonctions.h` et `fonctions.cpp` ne seront pas correctement inclus dans le projet.
10. Validez qu'il n'y a pas de fichiers non-commités. Corrigez la situation au besoin.
11. Poussez vos modifications sur votre *fork* GitHub.
12. Sur GitHub, créez un *pull request* à partir de votre branche `ajouter-fonction` en conservant les options par défaut. Cela aura pour effet de créer un *pull request* sur le dépôt de départ à partir de votre *fork*. C'est comme ça qu'on contribue à un projet *open source*!
