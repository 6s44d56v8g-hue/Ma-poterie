# digital pottery — mise en ligne

Le site est 100 % statique : aucun serveur, aucune base de données, aucune requête vers des services externes (police et three.js sont inclus).

## Tester chez toi
Double-clique sur `index.html`.

## Publier sur GitHub Pages
1. Dans ton dépôt, supprime les anciens fichiers du site.
2. **Add file → Upload files**, puis glisse **tout le contenu de ce dossier** : `index.html`, le dossier `assets`, `robots.txt`, `.nojekyll`, `README.md`. `index.html` doit être à la racine du dépôt.
3. **Commit changes**, attends 1 à 2 minutes. L'onglet **Actions** doit afficher « Success ».
4. Ouvre l'adresse indiquée dans **Settings → Pages** et recharge sans cache (Cmd+Maj+R).

Les avertissements « Node.js 20 deprecated » et « ubuntu-latest will migrate » dans Actions viennent de GitHub : ils ne bloquent rien.

## Avant de communiquer le lien
- Le bouton « Acheter » est une démonstration : il affiche le récapitulatif et le plan technique, mais aucun paiement n'est pris. Pour vendre vraiment, il faut brancher un service de paiement (Stripe, Shopify, etc.).
- Un site qui vend en France demande des mentions légales et des CGV.
- Le site n'utilise ni cookie ni traceur : pas de bandeau nécessaire tant que tu n'en ajoutes pas.
