# Romans

Point d’entrée pour lire ou organiser tes traductions / romans en Markdown.

## Accès rapide par roman

| Roman | Premier chapitre | Dernier paru | Liste des chapitres |
|-------|------------------|--------------|---------------------|
| Exemple | [Chapitre 1](exemple-roman/chapitres/001.md) | [Index](exemple-roman/index.md) |

> **Astuce :** à chaque nouveau chapitre, mets à jour la colonne **Dernier paru** dans ce tableau et ajoute une ligne dans l’`index.md` du roman.

---

## Ajouter un nouveau roman

1. **Créer le dossier**  
   `novels/<slug-du-roman>/`  
   Exemple : `novels/ma-fantaisie/`

2. **Copier l’index**  
   Duplique `novels/exemple-roman/index.md` vers `novels/<slug>/index.md`, puis remplace le titre et la liste des chapitres.

3. **Créer les chapitres**  
   Un fichier par chapitre, par ex. `novels/<slug>/chapitres/001.md`, `002.md`, …  
   Numérotation fixe sur **3 chiffres** pour que l’ordre reste clair dans l’explorateur de fichiers.

4. **Enregistrer ce README**  
   Ajoute une **ligne** au tableau *Accès rapide par roman* avec les liens :
   - premier : toujours `chapitres/001.md` (ou ton premier fichier) ;
   - dernier : le fichier du chapitre le plus récent ;
   - liste : `index.md` du roman.

---

## Convention des chemins

```
novels/
├── README.md                 ← ce fichier (hub)
└── <slug>/
    ├── index.md              ← tous les chapitres → liens .md
    └── chapitres/
        ├── 001.md
        ├── 002.md
        └── ...
```

Les liens entre fichiers utilisent des **chemins relatifs** depuis la racine du dépôt (comme dans le tableau ci-dessus), ce qui fonctionne sur GitHub, GitLab et dans la plupart des éditeurs Markdown.
