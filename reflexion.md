1. Structure du projet
Le projet suit un modèle collaboratif avec fusion. Les développeurs travaillent sur des branches séparées (Bilel, Yassir, Kasper) qui convergent vers la branche principale via des merges. L'historique n'est pas linéaire mais "en râteau" (divergences et convergences).

2. git fetch vs git pull
fetch : Télécharge les nouveautés du serveur sans toucher à votre code (sécurisant).

pull : Télécharge et fusionne immédiatement (plus rapide, mais risque de conflits).

Exemple : On utilise fetch pour inspecter le travail des autres avant de décider de l'intégrer.

3. git reset vs git revert
reset : Efface les commits (supprime l'historique).

revert : Annule un commit en en créant un nouveau (préserve l'historique).

Risque : Utiliser reset sur une branche partagée est dangereux car cela casse l'historique pour tous les autres collaborateurs.
