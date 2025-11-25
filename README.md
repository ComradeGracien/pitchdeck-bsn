[README.md](https://github.com/user-attachments/files/23742170/README.md)
# BSN Premium G&S Consulting - Pitch Deck E.L.I.T.E.™

## 🚀 Présentation Interactive HTML

Pitch deck premium pour **BSN Premium G&S Consulting** présentant la méthodologie **E.L.I.T.E.™** avec calculateur ROI interactif.

### ✨ Fonctionnalités

- **13 slides premium** avec dégradés verts sophistiqués
- **Calculateur ROI interactif** en temps réel (JavaScript)
- **Navigation fluide** (clavier + boutons)
- **Design responsive** (ordinateur, tablette, mobile)
- **Liens d'agenda intégrés** pour conversion directe
- **Charte graphique cohérente** (vert foncé/or/blanc)

### 📋 Contenu des Slides

1. **Couverture** - Logo BSN + Slogan "Structurer - Scaler - Gagner"
2. **Le Problème** - Pourquoi les PME stagnent
3. **La Vérité** - Message impactant
4. **Notre Mission** - Excellence et croissance durable
5. **Pourquoi BSN ?** - Modèle hybride unique
6. **Notre Promesse** - +30% de croissance
7. **Nos Domaines d'Intervention** - 6 piliers d'expertise
8. **Méthodologie E.L.I.T.E.™** - Framework en 5 étapes
9. **⭐ Calculateur ROI Interactif** - Impact BSN en temps réel
10. **Résultats & Cas Clients** - 4 transformations réelles
11. **Nos Offres** - ELITE Starter (3 mois) vs Scale (6 mois)
12. **Notre Garantie** - Engagement résultat
13. **Call to Action** - Liens agenda + Prix 400€

### 🎮 Navigation

- **Flèches clavier** : ← → pour naviguer
- **Barre d'espace** : Slide suivante
- **Chiffres 1-9** : Aller à la slide directement
- **Boutons** : Précédent/Suivant en bas de l'écran

### 🧮 Calculateur ROI

Le calculateur de la slide 9 permet aux prospects de :
- Saisir leurs données actuelles (CA, employés, taux de conversion...)
- Voir l'impact projeté de BSN en temps réel
- Calculer le ROI sur 12 mois automatiquement

## 📦 Déploiement

### Option 1: GitHub Pages (Gratuit)

1. **Créer un repository GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - BSN Pitch Deck"
   git branch -M main
   git remote add origin https://github.com/VOTRE-USERNAME/bsn-pitch-deck.git
   git push -u origin main
   ```

2. **Activer GitHub Pages**
   - Aller dans Settings → Pages
   - Source : Deploy from a branch
   - Branch : main / (root)
   - Sauvegarder

3. **Votre pitch deck sera accessible à :**
   ```
   https://VOTRE-USERNAME.github.io/bsn-pitch-deck/
   ```

### Option 2: Netlify (Gratuit)

1. **Via Git** (Recommandé)
   - Connecter votre repository GitHub à Netlify
   - Déploiement automatique à chaque commit

2. **Via glisser-déposer**
   - Aller sur [netlify.com](https://netlify.com)
   - Glisser le dossier du projet dans la zone de déploiement
   - URL générée automatiquement (ex: `https://amazing-name-123456.netlify.app`)

### Option 3: Vercel (Gratuit)

1. **Installation**
   ```bash
   npm install -g vercel
   ```

2. **Déploiement**
   ```bash
   vercel
   ```
   - Suivre les instructions
   - URL générée automatiquement

### Option 4: Hébergement Web Classique

1. **Upload via FTP/SFTP**
   - Télécharger le fichier `index.html` sur votre serveur web
   - Accessible via `https://votre-domaine.com/pitch-deck/`

2. **Serveurs supportés**
   - Apache
   - Nginx
   - IIS
   - Tout serveur web statique

## 🔧 Personnalisation

### Modifier les liens d'agenda

Dans `index.html`, rechercher et remplacer :
- `https://taap.it/session-offerte-bsn` → Votre lien session premium
- `https://taap.it/diagnostic-to-scale-bsn` → Votre lien diagnostic

### Ajuster les calculs du ROI

Dans le script JavaScript, modifier les variables :
```javascript
const reductionTachesRepetitives = 0.40; // 40% de réduction
const ameliorationTauxConversion = 0.20; // +20% d'amélioration
const investissementBSN = 25000; // 25 000€ d'investissement
```

### Changer les couleurs

Dans le CSS, modifier :
```css
:root {
  --vert-fonce: #0d3025;
  --vert-clair: #1a3d2e;
  --or: #c8a876;
  --or-clair: #b8975f;
}
```

## 📱 Compatibilité

- ✅ **Chrome** 80+
- ✅ **Firefox** 75+
- ✅ **Safari** 13+
- ✅ **Edge** 80+
- ✅ **Mobile** iOS Safari, Chrome Mobile

## 📊 Analytics (Optionnel)

Pour suivre les consultations, ajouter Google Analytics :

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🆘 Support

En cas de problème :
1. Vérifier que le fichier `index.html` est bien à la racine
2. Tester localement avec un serveur web local
3. Vérifier la console du navigateur pour les erreurs JavaScript

## 📄 Licence

© 2024 BSN Premium G&S Consulting. Tous droits réservés.

---

**🚀 Votre pitch deck est prêt à conquérir de nouveaux clients !**

Partagez simplement l'URL de déploiement avec vos prospects pour une expérience premium interactive.
