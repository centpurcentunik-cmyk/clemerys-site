# Clémérys

Site vitrine statique pour Clémérys.

Le site public présente l'univers de la marque, les familles de produits et les informations de contact.
Les livrets PDF ne sont pas listés publiquement : ils sont accessibles via les pages QR dédiées.

## Pages publiques

- `/`
- `/mon-livret/`
- `/livrets/`
- `/a-propos/`
- `/contact/`

## Pages QR non indexées

- `/q/baume/`
- `/q/huile/`
- `/q/bougie/`
- `/q/pack-mystere/`

Les pages QR contiennent une balise `noindex, nofollow`.
Le fichier `robots.txt` bloque aussi `/q/`.

## Important avant impression

Les QR codes générés dans `assets/qr/` pointent actuellement vers l'adresse locale de test.
Avant impression, il faut les régénérer avec le vrai nom de domaine.
