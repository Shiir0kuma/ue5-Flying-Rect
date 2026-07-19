**Présentation :**

Exercice technique réalisé dans le cadre d'une candidature en alternance.
Il s'agit d'un environnement Unreal Engine 5.7.4, dans laquelle un bloc rectangulaire se déplace librement via des entrées clavier de l'utilisateur

**Choix Techniques :**

J'ai choisi d'utiliser Blueprint plutôt que C++, je découvrais Unreal Engine pour la première fois et le Blueprint permet un apprentissage et une compréhension plus rapide et simple de la logique et plus gobalement comment utiliser UnrealEngine.
De plus j'ai déjà utilisé le langage C lors de mes études qui se rapproche de la logique C++. Cela m'a permet aussi de découvrir un nouveau type de langage de programmation.

J'ai utilisé un Rectangle plutôt qu'un personnage humanoïde car je voulais avant tout rester dans la simplicité et pouvoir découvrir l'interface et l'utilisation de l'UnrealEngine, sans devoir me confronter a d'autres problèmes (Saut / animation / Colision / Gravité...).

Pour le déplacement j'ai utilisé le système d'input standard d'UE5 :
- un Input Mapping Context (IMC_Car) qui associe les touches physiques à des actions abstraites,
- une Input Action de type Axis2D (IA_Move) pour l'avancement/recul et la rotation, avec des modificateurs Swizzle et Negate pour rediriger correctement chaque touche vers le bon axe,
- une Input Action de type Axis1D (IA_UpDown) pour le déplacement vertical.

**Contrôles :**

Z : Avancer
S : Reculer
Q : Tourner à gauche
D : Tourner à droite
Espace : Monter
Crtl Gauche : Descendre

**Lancer le projet :**

1. Installez Unreal Engine 5.7.4
2. Cloner ce repo : git clone <url>
3. Ouvrir le fichier RectDemo.uproject
4. Cliquer sur "Play" dans l'éditeur


**Utilisation de l'IA :**

J'ai utilisé Claude comme assistant pour l'apprentissage tout au long de l'exercice. Ayant aucune expérience avec Unreal Engine j'ai demandé à Claude de fournir une documentation des concepts fondamentaux de UnrealEngine.
De plus je l'ai utilisé pour me guider durant toutes les étapes de l'exercice sans écrire ni configurer à ma place, il m'apportais des détails techniques, et des guides pour configurer et réaliser les blueprint.
