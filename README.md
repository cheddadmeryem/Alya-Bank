# CV - Alya Bank (site statique)

Ce dépôt contient une page statique pour présenter mon CV et le projet fintech "Alya Bank".

Fichiers principaux
- index.html — page d'accueil / CV
- style.css — styles
- README.md — cette documentation
- CNAME — nom de domaine personnalisé

Déployer via GitHub Pages
1. Dans GitHub → Settings → Pages :
   - Source: Branch -> main (ou master) / Folder -> root
2. Ajouter le domaine personnalisé : `alya-bank.com` (ou je peux le faire pour toi dans Settings → Pages si tu veux).
3. Attendre la propagation DNS et le provisionnement du certificat HTTPS (quelques minutes à quelques heures).

DNS à ajouter chez ton registrar (pour alya-bank.com)
- A 185.199.108.153
- A 185.199.109.153
- A 185.199.110.153
- A 185.199.111.153

Optionnel : ajouter un CNAME pour www
- CNAME www -> cheddadmeryem.github.io

Fichier CNAME
- Le fichier CNAME contient :
  alya-bank.com

Modifier le contenu
- Edite `index.html` pour remplacer le nom, email, liens et le lien démo.
- Pour ajouter un CV téléchargeable, ajoute `cv.pdf` à la racine et un lien vers ce fichier.

Contact
- Si tu veux que je modifie le design ou ajoute des captures d'écran / logo, envoie les assets et je les intègre.
