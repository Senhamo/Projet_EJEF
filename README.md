<<<<<<< HEAD
# ONG Solidarité - Site Web

Un site web moderne et professionnel pour une organisation non gouvernementale (ONG) dédiée à l'aide humanitaire et au développement durable.

## 🌟 Fonctionnalités actuelles

### Pages principales
- **Page d'accueil** : Présentation générale avec hero section vidéo, statistiques et domaines d'intervention
- **À propos** : Histoire de l'ONG, valeurs et équipe
- **Nos missions** : Détail des actions par domaine avec vidéos de témoignages
- **Galerie vidéos** : Collection complète de vidéos par catégories (aide humanitaire, éducation, développement, témoignages)
- **Contact** : Formulaire de contact, coordonnées et FAQ

### Caractéristiques techniques
- Design responsive et moderne adapté à tous les appareils
- Navigation fluide avec menu mobile
- Animations et effets interactifs
- Formulaire de contact fonctionnel avec validation
- Sections FAQ dynamiques
- Compteurs animés pour les statistiques
- Police Google Fonts (Inter) et icônes Font Awesome
- **Nouveau** : Intégration complète de vidéos

## 🎥 Fonctionnalités vidéo

### Page d'accueil
- **Hero section avec vidéo de fond** : Vidéo en plein écran avec overlay sombre
- **Section témoignages vidéo** : Vidéos de bénéficiaires avec aperçu et lecture

### Page missions
- **Vidéos par domaine d'intervention** : YouTube embeds pour chaque type de mission
- **Descriptions contextuelles** : Statistiques et informations sur chaque vidéo

### Page galerie vidéos
- **Filtrage par catégories** : Boutons pour filtrer (toutes, humanitaire, éducation, développement, témoignages)
- **Grille responsive** : Mise en page adaptative des vidéos
- **Lecteur HTML5** : Vidéos auto-hébergées avec contrôles natifs
- **Vidéo mise en avant** : Section avec statistiques de visionnage
- **Effets interactifs** : Overlay de lecture, animations au survol

## 📁 Structure des fichiers

```
/
├── index.html          # Page d'accueil avec hero vidéo
├── about.html          # Page À propos
├── missions.html       # Page Nos missions avec vidéos
├── videos.html         # Page Galerie vidéos complète
├── contact.html        # Page Contact
├── css/
│   └── style.css       # Styles principaux (styles vidéo inclus)
├── js/
│   └── main.js         # JavaScript interactif
└── README.md           # Documentation
```

## 🚀 Pages et fonctionnalités

### Accueil (`index.html`)
- Hero section avec vidéo de fond et overlay sombre
- Statistiques clés de l'ONG
- Présentation des domaines d'intervention
- Section témoignages vidéo avec aperçus
- Section d'appel au don

### À propos (`about.html`)
- Histoire et mission de l'ONG
- Valeurs fondamentales
- Présentation de l'équipe

### Missions (`missions.html`)
- Détail des trois grands domaines d'intervention
- Vidéos YouTube intégrées pour chaque domaine
- Statistiques par domaine
- Projets phares

### Galerie vidéos (`videos.html`)
- Collection complète de vidéos organisées par catégories
- Système de filtrage dynamique
- Vidéo mise en avant avec statistiques
- Grille responsive de vidéos

### Contact (`contact.html`)
- Coordonnées complètes
- Formulaire de contact avec validation
- FAQ interactive

## 🎨 Styles et design

### Palette de couleurs
- **Primaire** : Bleu (#2563eb, #3b82f6)
- **Secondaire** : Orange (#f97316, #ea580c)
- **Succès** : Vert (#10b981)
- **Texte** : Gris foncé (#1f2937, #374151)
- **Fond** : Gris clair (#f8fafc, #f3f4f6)

### Typographie
- Police principale : Inter (Google Fonts)
- Tailles de police adaptatives
- Hiérarchie claire des titres

### Styles vidéo
- **Hero vidéo** : Plein écran avec overlay sombre (rgba(0,0,0,0.4))
- **Conteneurs vidéo** : Ratio 16:9 responsive
- **Overlay lecture** : Icône play centrée avec effet hover
- **Catégories vidéo** : Boutons de filtrage ronds
- **Effets** : Transitions fluides, transformations au survol

## ⚡ Interactivité JavaScript

### Fonctionnalités implémentées
- Menu mobile responsive
- Smooth scrolling
- Validation de formulaire
- FAQ accordion
- Animations au défilement
- Compteurs animés
- Effets de hover et ripple
- **Filtrage vidéo** : Système de catégories dynamique
- **Lecteur vidéo** : Contrôles natifs HTML5

## 📱 Responsive design

Le site est entièrement responsive avec des points de rupture pour :
- Desktop (1200px+)
- Tablette (768px - 1199px)
- Mobile (- 767px)

### Responsive vidéo
- Hero vidéo : hauteur réduite sur mobile (60vh vs 80vh)
- Grilles vidéo : passage à 1 colonne sur petits écrans
- Boutons de catégorie : taille réduite
- Lecteurs vidéo : pleine largeur avec ratio conservé

## 🌐 Navigation

### Menu principal
- Accueil : `/index.html`
- À propos : `/about.html`
- Nos missions : `/missions.html`
- Nos vidéos : `/videos.html`
- Contact : `/contact.html`

### Appels à l'action
- Boutons principaux vers les pages missions et contact
- Liens vers galerie vidéo depuis hero et sections
- Réseaux sociaux (liens à personnaliser)

## 🔧 Personnalisation

### Informations à modifier
```
Nom de l'ONG : ONG Solidarité
Adresse : 123 Rue de l'Espoir, 75000 Paris
Email : contact@ong-solidarite.org
Téléphone : +33 (0)1 23 45 67 89
```

### Vidéos à personnaliser
- URLs des vidéos YouTube dans `missions.html`
- Sources vidéo dans `videos.html` et `index.html`
- Images de remplacement (posters) pour les vidéos
- Titres et descriptions des vidéos

### Statistiques à mettre à jour
- Nombre de vies améliorées
- Nombre de pays intervenus
- Nombre de projets réalisés
- Nombre de bénévoles actifs
- Statistiques de visionnage vidéo

### Images à remplacer
- Placeholder d'images dans la section équipe
- Icônes de domaines d'intervention
- Photos de projets
- Posters vidéo (images de prévisualisation)

## 🚀 Déploiement

Pour déployer le site :

1. Personnaliser le contenu (textes, coordonnées, statistiques)
2. Remplacer les URLs vidéo par vos propres vidéos
3. Ajouter des posters/preview images pour les vidéos
4. Tester la lecture vidéo sur différents appareils
5. Optimiser la taille des fichiers vidéo pour le web
6. Publier via le **Publish tab** pour le mettre en ligne

## 📈 Améliorations futures recommandées

### Fonctionnalités à ajouter
- Système de don en ligne sécurisé
- Newsletter et gestion des abonnés
- Galerie photo des projets
- Blog ou actualités
- Formulaire de candidature bénévole
- Système de parrainage
- **Hébergement vidéo** : Utilisation de CDN pour les grandes vidéos
- **Sous-titres** : Ajout de sous-titres pour l'accessibilité
- **Qualité adaptative** : Vidéos en plusieurs qualités

### Optimisations
- Optimisation SEO avancée
- Performance et chargement
- Accessibilité (WCAG)
- Multi-langue
- **Lazy loading** : Chargement différé des vidéos
- **WebM format** : Support multiple formats vidéo

### Intégrations
- Réseaux sociaux (flux Instagram, Facebook)
- Google Analytics
- Système de paiement (Stripe, PayPal)
- CRM pour la gestion des contacts
- **YouTube API** : Intégration avancée avec chaîne YouTube
- **Vimeo** : Alternative d'hébergement vidéo

## 📞 Support

Pour toute question ou assistance concernant ce site web :
- Consulter la documentation du code
- Vérifier la console du navigateur pour les erreurs
- Tester les fonctionnalités sur différents navigateurs
- Vérifier la compatibilité des formats vidéo (MP4, WebM)
- Tester la responsive des lecteurs vidéo
- Contactez le développeur via le formulaire de contact

## 📹 Formats vidéo recommandés

### Formats supportés
- **MP4** : Format universel, recommandé pour la compatibilité
- **WebM** : Format moderne, meilleure compression
- **OGV** : Alternative open source

### Spécifications techniques
- **Ratio** : 16:9 pour la plupart des vidéos
- **Résolution** : 720p minimum, 1080p recommandé
- **Codec** : H.264 pour MP4, VP9 pour WebM
- **Taille** : Optimiser pour le web (< 50MB si possible)

### Hébergement vidéo
- **YouTube** : Gratuit, bonne diffusion, mais avec publicité
- **Vimeo** : Professionnel, sans publicité, payant
- **Self-hosting** : Contrôle total, mais nécessite optimisation

---

**ONG Solidarité - Construire un monde plus juste et solidaire** 🌍✨
=======
# Projet_EJEF
Projet de site web de l'ONG EJEF
>>>>>>> d9c98cd6214f41844a1f695bfbe36ced24e5c90d
