# À compléter (non public)

- Hébergeur du serveur : Microsoft Azure (VM `marega-1`, région Danemark Est, UE), nommé dans les politiques et les mentions légales depuis le 23/11/2026. OVH n'est plus l'hébergeur actuel (abandonné). Cloudflare n'est pas devant le serveur de jeu (Caddy en accès direct) : ne pas le citer comme sous-traitant tant que ça ne change pas.
- Cryptorche est devenu Zorvo : `cryptorche/` ne contient que des redirections vers `zorvo/`. Remplacer les anciennes URL dans les builds quand c'est possible.
- URL de politique dans l'appli Bras de Fer (`privacy-notice.ts`) : elle pointe vers `mrgmf.github.io/maregastudio-legal/bras-de-fer/{fr,en}.html`, pas vers ce site (`/marega-studio/bras-de-fer/confidentialite/`). À aligner (changer l'URL dans l'appli ou publier au même endroit), et renseigner `BRASDEFER_PRIVACY_URL` côté serveur.
- À valider avant publication : relecture par Fodié des nouvelles politiques (Zorvo, Bras de Fer, mentions légales), DPA archivés (Microsoft, Google, Apple), avis sur la certification HDS, export de données uniquement sur demande écrite (aucune route d'export dans les applis : à garder aligné avec le jeu et l'appli).
- Les pages et liens relatifs de ce site ont été corrigés (feuille de style et liens cassés en profondeur 2) ; vérifier en ligne après publication.
- Immatriculation de Marega Studio : SIREN/SIRET, forme juridique, adresse (ou domiciliation) à publier dans les mentions légales une fois obtenus.
- Durée légale de conservation des preuves d'achat (indiquée « en principe 10 ans ») : à valider.
- Page de consentement AdMob (UMP) et déclarations Data safety / App Privacy : à aligner quand AdMob sera intégré.
- Remplacer les URL `maregastudio.fr` par le domaine quand il sera acheté (le jeu pointe vers `https://maregastudio.fr/cryptorche/suppression-compte`) ; en attendant, mettre à jour `economy.gd` ou rediriger.
- Relecture juridique : validée par Fodié le 15/11 en l état.
