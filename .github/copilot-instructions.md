<!-- Copilot instructions for AI coding agents (FR) -->
# Brief pour les agents IA

But : aider un agent IA à être immédiatement productif dans ce dépôt "hello-world".

Contexte rapide
- Répertoire racine : `main.py` — script Python très simple qui affiche "Hello World!".
- `README.md` contient une seule ligne descriptive.
- Branche principale : `main` (propriétaire du dépôt : `Helwyr`).

Exemples de fichiers importants
- `main.py` : script exécutable directement. Exemple :
```
print("Hello World!")
```
- `README.md` : documentation minimale. Si vous modifiez le comportement, mettez-le à jour.

Comment exécuter & vérifier rapidement (PowerShell Windows)
- Lancer le script : `python main.py`  (ou `py -3 main.py` si plusieurs versions de Python)
- Vérifier la version de Python : `python --version`

Règles de contribution ciblées pour l'agent
- Préserver la simplicité : les changements doivent rester minimaux sauf demande explicite.
- Si vous ajoutez une nouvelle fonctionnalité :
  - Ajoutez des tests (préférer un dossier `tests/` avec `pytest`) et un `requirements.txt` si des dépendances sont nécessaires.
  - Mettez à jour `README.md` pour documenter le comportement et la commande d'exécution.
- Avant tout refactor significatif (création de package, ajout d'API, restructuration), demandez confirmation à l'utilisateur.

Comportement attendu de l'agent
- Expliquer brièvement chaque modification (une ligne) dans la description du commit.
- Pour les modifications de code, fournir un petit exemple de test ou commande pour reproduire le changement.
- Ne pas ajouter de dépendances sans justification explicite et sans fournir `requirements.txt`.

Notes spécifiques au dépôt
- Il n'y a pas de configuration de build ou de tests détectée. Si vous introduisez ces éléments, fournissez des instructions d'exécution claires dans le `README.md`.
- Préserver l'historique Git : faire des commits atomiques et proposer une PR vers `main`.

Questions à poser à l'utilisateur si incertain
- Voulez-vous que j'ajoute une suite de tests ?
- Voulez-vous convertir ce script en package (ex. `src/` + module) ?

Si un fichier `.github/copilot-instructions.md` existait, mergez le contenu utile plutôt que de l'écraser.

Fin.
