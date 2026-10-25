# HoliChrys.github.io

Blog personnel en Jekyll (thème minima), hébergé sur GitHub Pages : https://holichrys.github.io

## Écrire un article
Créer `_posts/AAAA-MM-JJ-titre.md` :

```markdown
---
layout: post
title: "Mon titre"
date: 2026-10-25 10:00:00 +0200
categories: blog
---
Contenu en Markdown.
```

Chaque push sur `main` reconstruit et déploie le site (`.github/workflows/jekyll.yml`).

## En local
```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

## Domaine perso (optionnel)
Ajouter un fichier `CNAME` contenant le domaine, et un enregistrement DNS CNAME vers `holichrys.github.io`.
