# Publication de la vitrine Dealwatch Europe

## Cible

- Dépôt distinct : `AymenBarka/dealwatch-europe-site`, public.
- Hébergement : GitHub Pages, branche `main`, répertoire `/(root)`.
- Site informatif statique, sans application transactionnelle ni SaaS.
- L'application principale conserve son dépôt privé ; aucune visibilité modifiée.

## Procédure de maintenance

1. Modifier uniquement les fichiers de cette vitrine, puis les examiner.
2. Prévisualiser à 1440 × 900 et 390 × 844, tester les ancres et le sous-chemin.
3. Vérifier l'absence de secrets, de ressources privées et de coordonnées non validées.
4. Commit et push sur `main` de ce dépôt public uniquement.
5. Dans GitHub : **Settings → Pages → Build and deployment**.
   Choisir **Deploy from a branch**, **main**, **/(root)**, puis **Save**.
6. Attendre la construction Pages, vérifier son résultat, l'URL retournée et
   l'affichage réel dans le navigateur. Un push seul n'atteste pas une publication réussie.

L'auteur Git utilise une adresse GitHub noreply pour ne pas exposer d'adresse
personnelle. Les captures et rapports de validation détaillés restent locaux.

## Validation de livraison

Vérification effectuée le **29 octobre 2026** :

- Site effectif : **https://aymenbarka.github.io/dealwatch-europe-site/**.
- Dépôt public : https://github.com/AymenBarka/dealwatch-europe-site.
- Publication initiale : commit `2e27d9835703355df161968458404886f70c51e8`.
- [Construction Pages initiale réussie](https://github.com/AymenBarka/dealwatch-europe-site/actions/runs/40902917553).
- API Pages : `built`, source `main` / `/`, HTTPS imposé.
- Requêtes HTTP publiques : page, CSS et favicon reçus avec statut 200,
  contenus identiques aux fichiers audités.
- Edge réel : 1440 × 900, 390 × 844, 320 × 568 et 768 × 1024,
  testés en local sous le sous-chemin puis après publication.
- Navigation par ancres, lien d'évitement au clavier et focus visible vérifiés.
- Aucun débordement horizontal, aucune erreur JavaScript ou HTTP, aucune
  ressource externe chargée, aucun formulaire ou lien fictif actif.
- Captures desktop et mobile examinées ; sept fichiers neufs seulement,
  sans secret ni dépendance au projet privé.
- Dépôt applicatif revérifié `PRIVATE`, sans changement de son contenu.

L'aperçu intégré au client a refusé la navigation vers le domaine. Les contrôles
HTTP et le navigateur Edge indépendant ont réussi ; ce refus d'aperçu ne vaut
pas échec de publication. Les rapports détaillés restent locaux et ne sont
pas nécessaires au fonctionnement du site.

## Revenir à la candidature Awin

La publication étant vérifiée, utiliser **https://aymenbarka.github.io/dealwatch-europe-site/** comme
présentation du projet dans le parcours officiel d'inscription éditeur Awin.
Décrire un prototype en développement, une vitrine informative et une plateforme
publique non encore disponible. Une URL publique ne constitue ni une approbation
du compte, ni un accord annonceur, ni un droit de stockage ou d'analyse des flux.
Les champs exacts du formulaire et les conditions doivent être vérifiés dans
le parcours actuel ; aucun compte ou programme n'est créé par cette publication.
