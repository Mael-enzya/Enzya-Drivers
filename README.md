# ENZYA DR — prototype

Prototype web mobile de démonstration pour Lubumbashi.

## Contenu
- `index.html` : application client / chauffeur / administration.
- Tarifs initiaux : course normale 3 000 CDF, booking 10 000 CDF.
- Numéros affichés : Vodacom 0828088525, Orange 085711127.

## Tester
Ouvrir `index.html` dans un navigateur moderne.

## Publier avec GitHub Pages
1. Ajouter `index.html` et `README.md` à la racine du dépôt GitHub.
2. Dans le dépôt, ouvrir **Settings → Pages**.
3. Dans **Build and deployment**, choisir **Deploy from a branch**.
4. Choisir la branche `main` et le dossier `/(root)`, puis **Save**.
5. Attendre la publication, puis ouvrir l'adresse GitHub Pages indiquée.

## Limites importantes
Cette version est un prototype local : les données sont enregistrées dans le navigateur de l'appareil. Les demandes ne sont pas partagées entre les téléphones. Le GPS n'est pas diffusé en direct. Les paiements, notifications push, authentification sécurisée et base de données multi-utilisateurs nécessitent un backend et une configuration de production. Ne pas utiliser pour transporter des clients avant ces développements et tests.
