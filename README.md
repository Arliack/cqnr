# Générateur de personnage — Ce qu'il nous reste (CQNR)

Application web mobile pour créer un personnage et générer la feuille de personnage CQNR remplie en PDF (A4 paysage).

## Fonctionnalités
- Formulaire simple : joueur·se, campagne, nom, concept, éclats ×3, marque, signes ×3
- Portrait avec recadrage (déplacement au doigt + zoom)
- Sauvegarde automatique sur l'appareil (localStorage)
- Interface FR / EN
- Génération de la feuille officielle remplie, aperçu puis téléchargement PDF

## Utilisation
Le fichier `index.html` est autonome (aucune dépendance locale) : ouvrez-le dans un navigateur, ou hébergez-le tel quel.

## Publier sur GitHub Pages
1. Créez un nouveau dépôt sur github.com (ex. `cqnr-generateur`)
2. Ajoutez `index.html` (et ce README) à la racine, puis commit + push
3. Dans le dépôt : Settings → Pages → Source : branche `main`, dossier `/ (root)`
4. Votre app sera en ligne sur `https://<votre-nom>.github.io/cqnr-generateur/`
