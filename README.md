# Aboubakar — Portfolio web & mobile

## Installation et lancement

```bash
npm install
npm run dev
```

Pour créer la version de production : `npm run build`. Pour la prévisualiser : `npm run preview`.

## Personnalisation

- Les projets de démonstration sont dans `src/data.js`. Remplacez-les par des projets réels et ajoutez leurs liens lorsqu'ils sont disponibles.
- Les compétences, services et technologies mobiles doivent être vérifiés et adaptés à l'expérience réelle d'Aboubakar.
- Le formulaire prépare un message WhatsApp : l'utilisateur doit confirmer son envoi dans WhatsApp. Aucun serveur de réception n'est configuré.
- Ajouter un sitemap et une URL Open Graph canonique après définition du domaine de production.

## Déploiement sur Vercel

Le projet Vercel doit être connecté à la branche qui contient le portfolio et avoir pour répertoire racine celui où se trouve ce fichier. La configuration `vercel.json` indique à Vercel d'exécuter `npm run build` et de publier `dist`. Utilisez Node.js 22 ou une version compatible avec la version de Vite installée. Après avoir envoyé les changements sur GitHub, lancez un nouveau déploiement depuis cette branche. Si une page reste vide, consultez les journaux de build et la console du navigateur.
