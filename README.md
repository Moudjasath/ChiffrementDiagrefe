# Chiffrement DE LORD GARNET
Chiffrement de Lord Garnet
Ce programme en C++ implémente une méthode de chiffrement de Lord Garnet.

Description
Le chiffrement de Lord Garnet , également appelé chiffrement de César, est une méthode de cryptographie où chaque lettre du texte est déplacée d'un certain nombre de positions dans l'alphabet. Dans cette implémentation spécifique, la méthode attribuée à Lord Garnet utilise un décalage pour chiffrer le texte en fonction de la clé donnée par l'utilisateur.

Utilisation
Prérequis
Pour exécuter ce code, assurez-vous d'avoir un compilateur C++ compatible.

Instructions
Téléchargement du code : Clonez ou téléchargez le fichier source chiffrement_garnet.cpp.

Compilation : Compilez le code à l'aide de votre compilateur C++ préféré. Par exemple :

g++ chiffrement_garnet.cpp -o chiffrement_garnet
Exécution : Exécutez le programme compilé :

./chiffrement_garnet
Entrées
Lors de l'exécution du programme, l'utilisateur est invité à entrer un texte à chiffrer. Ce texte peut contenir des lettres en minuscules. Ensuite, l'utilisateur est invité à entrer une clé, qui représente le décalage à appliquer au texte.

Fonctionnement du Code
Le code utilise un décalage pour chiffrer le texte en fonction de la clé entrée par l'utilisateur. Voici comment il fonctionne :

Chiffrement : Chaque lettre du texte est déplacée vers la droite dans l'alphabet selon la valeur de la clé. Par exemple, avec une clé de 3, 'a' devient 'd', 'b' devient 'e', et ainsi de suite.
Exemple
L'utilisateur est invité à entrer un texte (par exemple, "hello") et une clé (par exemple, 3). Le programme chiffre le texte en utilisant le décalage de 3 positions dans l'alphabet selon la méthode attribuée à Lord Garnet et affiche le texte chiffré.
![GARNET](https://github.com/Moudjasath/ChiffrementLORDGARNET/assets/140810316/67e081af-02ff-49c2-89d4-4575a1205d82)


