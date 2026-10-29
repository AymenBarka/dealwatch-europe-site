# Dealwatch Europe — Vitrine publique

Vitrine informative d'un projet de comparaison et de suivi des prix en cours
de développement. Le comparateur n'est pas accessible au public. Les accords
d'accès aux catalogues et les comparaisons commerciales actuelles restent à valider.

## Architecture

HTML5 et CSS3, sans JavaScript, framework, compilation, backend ou base de données.
Polices système, favicon et illustration SVG originaux locaux. Aucune dépendance
au dépôt applicatif privé, aucune image commerciale ni ressource distante.
Le code de l'application, ses rapports et ses données ne sont pas publiés ici.

## Modifier et prévisualiser

Modifier les textes dans `index.html` et les styles dans `styles.css`.
Conserver la distinction entre capacités du prototype, marchés envisagés et
résultats réellement validés. Aucun chiffre commercial, témoignage ou partenaire
ne doit être ajouté sans preuve et autorisation.

Depuis le dossier du site, avec Python installé :

```powershell
python -m http.server 8560 --bind 127.0.0.1
```

Ouvrir http://127.0.0.1:8560/ ; arrêter par Ctrl+C. Pour tester le sous-chemin,
servir le dossier parent puis ouvrir `/dealwatch-europe-site/`.
Les liens de ressources sont relatifs ; les URL canonical/Open Graph correspondent
au site public et doivent être mises à jour si son adresse change.

## Publication

Dépôt public : https://github.com/AymenBarka/dealwatch-europe-site

GitHub Pages : source `main`, répertoire `/(root)`, mode Deploy from a branch.
Le fichier `.nojekyll` conserve un déploiement statique direct.
Voir [DEPLOYMENT.md](DEPLOYMENT.md) pour les contrôles et l'adresse vérifiée.
Relire chaque fichier avant un commit puis ne pousser que le contenu de cette
vitrine. Le dépôt applicatif distinct doit rester privé.

## Contact et restrictions

Aucune adresse publique n'a été approuvée ; la rubrique Contact l'indique et
ne contient aucun faux lien. Pour activer un contact, faire valider explicitement
une adresse dédiée par le propriétaire, puis ajouter un lien `mailto:` dans cette
rubrique. Ne pas utiliser l'adresse personnelle d'un compte ou d'un commit.

Ne pas ajouter `.env`, clés, tokens, coordonnées personnelles, bases, catalogues,
rapports marchands, données clients ou code privé. La vitrine n'effectue aucune
collecte de prix, aucun envoi Telegram, aucune transaction et aucun appel API.
Elle n'ajoute ni formulaire, ni cookie, ni traceur. L'hébergement reste soumis
aux traitements techniques de GitHub ; il ne s'agit pas d'un service commercial
transactionnel ou SaaS.
