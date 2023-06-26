# TP Git

Nous allons composer des équipes de 4 personnes. L'objectif est de réaliser une petite page HTML / CSS / JS.

On a 4 parties importantes sur la page :

- Header (Menu avec logo) avec un bouton qui affiche toto dans la console
- Un contenu (Deux colonnes avec une image et un texte)
- Un autre contenu (Trois colonnes avec images et texte)
- Footer (Fond de couleur avec un texte copyright) avec un bouton qui affiche titi dans un h1

Chaque groupe aura UN SEUL dépôt Github. Pour créer ce dépôt, une personne prend la responsabilité de créer le dépôt sur son compte Github.

Le créateur devra créer un fichier HTML avec un DOCTYPE et un body vide, un fichier CSS vide lié à la page HTML et un fichier JS.

Ensuite, les trois autres personnes vont devoir être ajoutées sur le dépôt du "créateur".

Une fois que les personnes ont accès au dépôt sur Github, elles vont devoir "cloner" le dépôt :

```
cd Code
git clone https://github.com/cda-chty/discover-git.git
```

A cette étape, tous les membres ont le projet en commun sur leur machine.

Chaque membre va créer sa branche (header, footer, content ou content-2) puis va la pousser sur Github. Pour éviter des conflits sur le CSS, vous pouvez créer un fichier chacun (option).

Ensuite chacun va faire son travail, committer et push sur sa branche.

A la fin du projet, quand tout le monde a fini, chacun va créer une Pull Request avec sa branche et va la "merger" dans main.
