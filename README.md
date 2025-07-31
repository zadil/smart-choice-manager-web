# Smart Choice Manager - Site Web

Ce dossier contient le site web officiel pour l'add-on Smart Choice Manager pour Google Forms.

## Structure du projet

```
ChoiceEliminator2-Website/
├── index.html          # Page d'accueil principale
├── privacy.html        # Politique de confidentialité
├── styles.css          # Styles CSS
├── script.js           # JavaScript interactif
└── README.md           # Ce fichier
```

## Fonctionnalités du site

- **Design moderne et responsive** - Compatible mobile, tablette et desktop
- **Navigation fluide** - Défilement doux entre les sections
- **Animations interactives** - Effets visuels au scroll et hover
- **Démo interactive** - Aperçu du fonctionnement de l'add-on
- **Politique de confidentialité complète** - Conforme aux exigences Google

## Options de déploiement

### 1. GitHub Pages (Gratuit)

1. Créez un nouveau repository sur GitHub
2. Uploadez tous les fichiers de ce dossier
3. Allez dans Settings > Pages
4. Sélectionnez "Deploy from a branch" > "main"
5. Votre site sera disponible à `https://votre-username.github.io/nom-du-repo`

### 2. Netlify (Gratuit)

1. Allez sur [netlify.com](https://netlify.com)
2. Glissez-déposez ce dossier sur Netlify
3. Votre site sera automatiquement déployé avec une URL personnalisée

### 3. Vercel (Gratuit)

1. Allez sur [vercel.com](https://vercel.com)
2. Connectez votre repository GitHub
3. Déploiement automatique à chaque commit

### 4. Hébergement personnalisé

Uploadez les fichiers sur votre serveur web via FTP/SFTP.

## Personnalisation requise

Avant le déploiement, modifiez les éléments suivants :

### Dans `index.html` et `privacy.html` :
- Remplacez `your-username` par votre nom d'utilisateur GitHub réel
- Mettez à jour l'email de contact : `support@smartchoicemanager.com`
- Ajustez les liens vers votre repository

### Dans `appsscript.json` (projet principal) :
- Mettez à jour `homepageUrl` avec l'URL de votre site déployé
- Mettez à jour `privacyPolicyUrl` avec l'URL de votre politique de confidentialité

## Exemple d'URLs après déploiement

Si vous déployez sur GitHub Pages :
```json
{
  "homepageUrl": "https://votre-username.github.io/ChoiceEliminator2-Website",
  "privacyPolicyUrl": "https://votre-username.github.io/ChoiceEliminator2-Website/privacy.html"
}
```

## Maintenance

- Mettez à jour la date dans la politique de confidentialité lors de modifications
- Ajoutez des captures d'écran de l'add-on dans le dossier `images/` si nécessaire
- Testez régulièrement la compatibilité mobile

## Support

Pour toute question concernant le site web, consultez la documentation ou contactez le support.
