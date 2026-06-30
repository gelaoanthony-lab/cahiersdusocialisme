# Guide : comment publier un article sur Cahiers du Socialisme

Ce guide explique comment ajouter un nouvel article, directement depuis votre navigateur, sans rien installer sur votre ordinateur.

## Étape 1 — Aller sur GitHub

Rendez-vous sur la page de votre dépôt :
`https://github.com/gelaoanthony-lab/cahiersdusocialisme`

## Étape 2 — Ouvrir le dossier des articles

Cliquez sur le dossier `content`, puis sur le dossier `posts`.

## Étape 3 — Créer un nouveau fichier

1. Cliquez sur le bouton **"Add file"** (en haut à droite de la liste de fichiers)
2. Choisissez **"Create new file"**
3. Donnez un nom à votre fichier, par exemple : `jaures-et-le-socialisme.md`

⚠️ Important : le nom du fichier doit toujours se terminer par `.md`, sans espaces (utilisez des tirets `-` à la place).

## Étape 4 — Écrire votre article

Copiez-collez ce modèle en haut du fichier, puis adaptez-le :

```
---
title: "Titre de votre article"
date: 2026-06-30
draft: false
tags: ["jaurès", "socialisme"]
---

Le texte de votre article commence ici.

Vous pouvez créer un nouveau paragraphe simplement en sautant une ligne.

## Un sous-titre

Le texte continue sous ce sous-titre.
```

Quelques règles simples de mise en forme (Markdown) :
- `**texte**` → **texte en gras**
- `*texte*` → *texte en italique*
- `## Titre` → un sous-titre
- `> citation` → une citation mise en valeur

## Étape 5 — Ajouter une image (optionnel)

1. Uploadez d'abord votre image dans le dossier `static/images` (même méthode : "Add file" → "Upload files")
2. Puis dans votre article, insérez-la ainsi :
```
![Description de l'image](/images/nom-de-votre-image.jpg)
```

## Étape 6 — Publier

En bas de page, cliquez sur le bouton vert **"Commit changes..."**, puis confirmez.

C'est tout ! Le site se met à jour automatiquement en 1 à 2 minutes. Vous pouvez suivre la progression dans l'onglet **"Actions"** de votre dépôt (une coche verte ✅ signifie que c'est en ligne).

## Modifier un article existant

Ouvrez le fichier de l'article dans `content/posts/`, cliquez sur l'icône en forme de crayon (✏️) en haut à droite pour éditer, modifiez le texte, puis "Commit changes" comme ci-dessus.
