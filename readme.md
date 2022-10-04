# Notes de cours Latex

Repository pour version control notes de cours et devoirs.
Pour sync un folder d'un cours dans un subrepo;
- Créer le folder SIGXXXX_Latex dans le folder du cours et créer SIGXXXX dedans
- cd dans SIGXXXX_Latex
- git init
- git config core.sparseCheckout true
- git remote add -f origin https://github.com/Fredlague/Notes_Latex
- echo "SIGXXXX/*" > .git/info/sparse-checkout
- git checkout main
