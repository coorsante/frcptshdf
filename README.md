# Site web – FRCPTS Hauts-de-France

Site vitrine de la Fédération Régionale des CPTS Hauts-de-France.
Site statique (HTML/CSS/JS, sans dépendance), prêt pour GitHub Pages.

## Contenu
- `index.html` : la page du site (logo animé, fédération, gouvernance, adhésion, agenda, actualités, contact)
- `assets/logo-frcpts.png` : logo original
- `docs/bulletin-adhesion-2026.pdf` et `docs/statuts-frcpts-hdf.pdf` : documents téléchargeables

## Mise en ligne sur GitHub Pages
1. Créer un dépôt sur github.com (par ex. `frcpts-hdf`), public.
2. « Add file » > « Upload files » : glisser tout le contenu de ce dossier (pas le dossier lui-même), puis « Commit changes ».
3. Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`, Save.
4. Le site est en ligne après une minute à l’adresse `https://<compte>.github.io/frcpts-hdf/`.

Nom de domaine personnalisé (ex. frcpts-hdf.fr) : Settings > Pages > Custom domain.

## Mettre à jour
- Actualités et agenda : sections `#actualites` et `#agenda` dans `index.html`.
- Nouveau bulletin : remplacer le PDF dans `docs/` en gardant le même nom.
