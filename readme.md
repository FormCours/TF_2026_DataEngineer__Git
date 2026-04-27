# Demo 01

Ceci est le premier fichier dans le git !  👈(ﾟヮﾟ👈)

## Commande 
### Initialiser git
```
git init
```

### Configurer les informations "user" pour les commits (Doc)
```
# Configuration
git config --global user.name "Della Duck"
git config --global user.email "della.duck@tftic.be"

# Editer la config
git config --global --edit
git config --edit
```
_L'option "--global" permet de faire une configration globale à la machine._

### Ajouter des modifications dans git 
```
# Ajouter tous les fichiers
git add .


# Ajouter ...
git add *

# Ajouter un fichier
git add <path-file>
```

### Valider des fichiers
```
git commit -m "Votre sublime message de commitage 🦊"
```


## Fonctionnement de git 

### Fichier non-suivi
Utilisation de `git add` pour traquer les fichiers.

### Fichier suivi
- Staged (En attente de validation)
Fichiers non-suivi ou modifié après un `git add`.

- Validate
Fichiers validés via `git commit`.

- Modified
Fichiers validés qui ont été modifiés.


## Le fichier ".gitignore"
Permet à git d'ignorer des fichiers et des dossiers

[Template de gitignore](https://github.com/github/gitignore)


## Les repositories en ligne _(GitHub, GitLab, Bitbucker, Azure Devops, ...)_

### Config le lien entre le repo local et le distant
```
# Exemple générique
git remote add <name-remote> <branch>

# Exemple réel
git remote add origin main
```

### Envoyer le repo local vers le distant
```
# Exemple en precisant le nom de la remote et de la branche
git push origin main

# Exemple en configurant le nom de la remote et de la branche
git push -u origin main

# Exemple si l'upstream est config
git push
```
