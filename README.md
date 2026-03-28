# Romans

Point d’entrée pour lire ou organiser tes traductions / romans en Markdown.

## Accès rapide par roman

| Roman | Premier chapitre | Dernier paru | Liste des chapitres |
|-------|------------------|--------------|---------------------|
| Cycles des vies fragmentées | [Chapitre 1](Cycles%20des%20vies%20fragmentées/chapitres/001.md) | [Chapitre 2](Cycles%20des%20vies%20fragmentées/chapitres/002.md) | [Index](Cycles%20des%20vies%20fragmentées/index.md) |

> **Astuce :** à chaque nouveau chapitre, mets à jour la colonne **Dernier paru** dans ce tableau et ajoute une ligne dans l’`index.md` du roman.

---

## Ajouter un nouveau roman

1. **Créer le dossier à la racine du dépôt** (à côté de ce `README.md`)  
   Exemple : `Ma fantaisie/`

2. **Créer l’index**  
   Copie `Cycles des vies fragmentées/index.md` vers `Ma fantaisie/index.md`, change le titre et la liste des chapitres.

3. **Créer les chapitres**  
   Dossier `Ma fantaisie/chapitres/` avec un fichier par épisode : `001.md`, `002.md`, …  
   Numérotation sur **3 chiffres** pour un tri clair dans l’explorateur.

4. **Mettre à jour ce README**  
   Ajoute une **ligne** au tableau *Accès rapide par roman* :
   - **Premier chapitre** → ton `chapitres/001.md` (ou équivalent) ;
   - **Dernier paru** → le dernier fichier publié ;
   - **Liste des chapitres** → `index.md` du roman.

---

## Convention des dossiers

```
<racine-du-dépôt>/
├── README.md                 ← ce fichier (hub)
└── <nom-du-roman>/
    ├── index.md              ← tous les chapitres → liens .md
    └── chapitres/
        ├── 001.md
        ├── 002.md
        └── ...
```

Les liens du tableau utilisent des chemins relatifs depuis ce fichier. Les **espaces** dans les noms de dossiers sont encodés en `%20` dans les URLs pour que les liens restent valides sur GitHub / GitLab et dans la plupart des visionneuses Markdown.
