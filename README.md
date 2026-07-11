# Générateur de personnage — Ce qu'il nous reste (CQNR)

Application web mobile pour créer un personnage et générer la feuille de personnage CQNR remplie en PDF (A4 paysage).

## Fonctionnalités
- Formulaire simple : joueur·se, campagne, nom, concept, éclats ×3, marque, signes ×3
- Portrait avec recadrage (déplacement au doigt + zoom)
- Sauvegarde automatique sur l'appareil (localStorage)
- Interface FR / EN
- Génération de la feuille officielle remplie, aperçu puis téléchargement PDF

## Utilisation
Ouvrez `index.html` dans un navigateur. **Important : le dossier `assets/` doit être à côté de `index.html`** (la feuille vierge y est chargée pour générer le PDF).

## Publier sur GitHub Pages
1. Dans votre dépôt (ex. `Arliack/cqnr`) : Add file → Upload files
2. Ajoutez `index.html`, `README.md` **et le dossier `assets/`** (glissez le dossier entier), puis Commit
3. Settings → Pages → Source : branche `main`, dossier `/ (root)`
4. Votre app sera en ligne sur `https://arliack.github.io/cqnr/`
