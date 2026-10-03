# Team Arcadia images

Public hosting for the pictures shown on Team Arcadia project pages (CurseForge, Modrinth, websites).
The source repositories can stay private: pages load their pictures from here through jsDelivr.

## Layout

```
mods/<mod-id>/curseforge/      everything a CurseForge page loads (banners, titles, badges, divider)
mods/<mod-id>/curseforge/icons/        feature icons
mods/<mod-id>/curseforge/screenshots/  gallery pictures (uploaded to CurseForge by hand)
```

Address of a file: `https://cdn.jsdelivr.net/gh/Team-Arcadia/images@main/<path>`

| Project | Folder |
|---|---|
| Arcadia Games | `mods/arcadia-games/curseforge/` |
| My Girlfriend Laura | `mods/lauramod/curseforge/` |

## Rules

- Files are generated in each mod's repository (`images/`, by `images/tools/`) and copied here; never edit them by hand.
- Every file stays under 2 MB.
- After replacing a file, jsDelivr may serve the old one for up to 12 hours.

Author: vyrriox

---

# Images Team Arcadia (Version Française)

Hébergement public des images des pages de projets Team Arcadia (CurseForge, Modrinth, sites).
Les dépôts sources peuvent rester privés : les pages chargent leurs images d'ici via jsDelivr.

## Organisation

```
mods/<id-du-mod>/curseforge/              tout ce que charge une page CurseForge (bannières, titres, badges, séparateur)
mods/<id-du-mod>/curseforge/icons/        icônes des fonctionnalités
mods/<id-du-mod>/curseforge/screenshots/  images de galerie (envoyées à la main sur CurseForge)
```

Adresse d'un fichier : `https://cdn.jsdelivr.net/gh/Team-Arcadia/images@main/<chemin>`

| Projet | Dossier |
|---|---|
| Arcadia Games | `mods/arcadia-games/curseforge/` |
| My Girlfriend Laura | `mods/lauramod/curseforge/` |

## Règles

- Les fichiers sont générés dans le dépôt de chaque mod (`images/`, par `images/tools/`) puis copiés ici ; jamais modifiés à la main.
- Chaque fichier fait moins de 2 Mo.
- Après remplacement d'un fichier, jsDelivr peut servir l'ancien pendant 12 heures.

Auteur : vyrriox
