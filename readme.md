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

# Ajouter un fichier
git add <path-file>
```

### Valider des fichiers
```
git commit -m "Votre sublime message de commitage 🦊"
```

