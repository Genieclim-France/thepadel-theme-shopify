# 🎨 Guide de Personnalisation - Thème Shopify ThePadel

## 🚀 Démarrage Rapide

### 1. Installation des outils de développement
```bash
# Installer Shopify CLI
npm install -g @shopify/cli @shopify/theme

# Connecter votre store Shopify
shopify theme dev --store=votre-store.myshopify.com
```

### 2. Développement en local
```bash
# Lancer le serveur de développement
shopify theme dev

# Créer un nouveau thème sur votre store
shopify theme push --unpublished
```

## 🎯 Zones Principales à Personnaliser

### **1. Couleurs et Typographie**
📁 `config/settings_schema.json` - Configuration des couleurs dans l'admin
📁 `assets/base.css` - CSS principal du thème

### **2. Header/Navigation**
📁 `sections/header.liquid` - En-tête et navigation principale
📁 `sections/announcement-bar.liquid` - Barre d'annonces

### **3. Page d'Accueil**
📁 `templates/index.json` - Structure de la page d'accueil
📁 `sections/image-banner.liquid` - Bannière principale
📁 `sections/featured-collection.liquid` - Collections mises en avant

### **4. Pages Produits**
📁 `sections/main-product.liquid` - Template produit principal
📁 `sections/related-products.liquid` - Produits suggérés

### **5. Footer**
📁 `sections/footer.liquid` - Pied de page avec liens et informations

## 🏷️ Personnalisations Recommandées pour ThePadel

### Couleurs Suggérées
```css
/* Palette ThePadel */
--color-primary: #2E8B57; /* Vert padel */
--color-secondary: #FF6B35; /* Orange énergique */
--color-accent: #1E3A8A; /* Bleu sport */
--color-text: #1F2937; /* Gris foncé */
```

### Sections Spécifiques Padel
1. **Bannière Terrain** - Showcase des terrains
2. **Planning Réservations** - Intégration calendrier
3. **Équipements** - Catalogue raquettes/balles
4. **Témoignages** - Avis clients/joueurs

## 📱 Responsive & Performance
- ✅ Mobile-first par défaut
- ✅ Core Web Vitals optimisés
- ✅ Images adaptatives (WebP)
- ✅ Lazy loading intégré

## 🔧 Outils de Développement
- **Theme Check** - Validation du code
- **Prettier** - Formatage automatique
- **GitHub Actions** - CI/CD intégré

## ✅ Réalisations Complétées

### 🎨 **Header Personnalisé ThePadel**
- ✅ Design bleu moderne correspondant à votre maquette
- ✅ Logo "THE PADEL" stylisé
- ✅ Navigation : Accueil, Tournoi, Boutique, L'équipe The Padel, Contact
- ✅ Bouton vert "Réserver un terrain"
- ✅ Barre de recherche intégrée
- ✅ Menu mobile responsive avec overlay
- ✅ Icônes panier et compte utilisateur
- ✅ Header sticky avec animations

## 📞 Prochaines Étapes
1. **Tester le header** avec `shopify theme dev`
2. Créer les pages manquantes (équipe, contact, réservation)
3. Configurer les collections (tournoi)
4. Personnaliser la page d'accueil
5. Ajouter vos produits et collections

---
*Basé sur Dawn - Le thème de référence Shopify* 