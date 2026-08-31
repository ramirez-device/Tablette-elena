TABLETTE PERSONNELLE D'ELENA — VERSION HÉBERGEABLE

Contenu :
- index.html
- assets/elena-wallpaper.png

Hébergement :
1. Décompresse le dossier.
2. Envoie le contenu sur un hébergeur statique (GitHub Pages, Netlify, Cloudflare Pages, etc.).
3. L'adresse publique doit pointer vers index.html.
4. Dans le créateur d'item du serveur : Type d'item > Site Web > Add Page > colle cette URL.

Important :
- Journal, Recherches et Passé sont sauvegardés dans le stockage local du navigateur qui ouvre la tablette.
- Galerie et Dessins utilisent IndexedDB dans ce même navigateur.
- Cette version n'a pas encore de synchronisation serveur. Un autre joueur ouvrant la même URL ne récupérera pas automatiquement les données d'Elena.
- Pour une tablette réellement persistante et partageable entre joueurs, il faudra une petite base de données/API et éventuellement un identifiant propre à l'item.

Aucune compilation n'est nécessaire.

MISE À JOUR V4 :
- Journal : créer, modifier, enregistrer et supprimer des notes.
- Recherches : créer, modifier et supprimer des recherches.
- Observations : ajouter, modifier et supprimer chaque observation.
- Passé : créer, modifier et supprimer les éléments d'archive.

MISE À JOUR V5 — PASSÉ :
- Les sections (Voyages, Louise Carter, etc.) peuvent être ouvertes, renommées/modifiées et supprimées.
- La suppression d'une section demande confirmation et supprime aussi son contenu.
- Dans chaque section, chaque dossier peut être consulté, modifié et supprimé.
- Il est possible de créer de nouvelles sections et de nouveaux dossiers à l'intérieur.
