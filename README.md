# Soumission Budgétaire Interactive

Application web de création de soumissions budgétaires pour le domaine de la construction résidentielle au Québec.

## Description

Cette application permet de créer, gérer et exporter des soumissions budgétaires professionnelles. Conçue pour les entrepreneurs en construction, elle offre une interface intuitive avec calculs automatiques des taxes québécoises (TPS/TVQ) et des marges (administration, contingence, profit).

## Fonctionnalités

### Gestion des soumissions
- Création de soumissions avec numérotation automatique
- Sauvegarde automatique dans le navigateur (localStorage)
- Gestion de multiples soumissions sauvegardées
- Import/Export en format JSON
- Téléchargement en HTML autonome

### Calculs automatiques
- **8 catégories de construction** avec sous-totaux automatiques
- Calcul quantité × prix unitaire par item
- **Taxes québécoises** : TPS (5%) et TVQ (9.975%)
- **Marges ajustables** : Administration (3%), Contingence (12%), Profit (15%)
- Récapitulatif avec total général

### Personnalisation
- Logo d'entreprise personnalisable
- Informations complètes de l'entreprise (adresse, téléphone, RBQ, NEQ, TPS, TVQ)
- Titres de catégories et descriptions d'items modifiables
- Conditions et exclusions personnalisables

### Impression et export
- Mise en page optimisée pour impression (8½" × 11")
- Export HTML autonome avec toutes les données
- Export JSON pour sauvegarde externe

## Catégories de construction

1. **Travaux Préparatoires et Démolition** - Permis, études, démolition, préparation terrain
2. **Fondation, Infrastructure et Services** - Excavation, fondation, drainage, raccordements
3. **Structure et Charpente** - Plancher, murs, toit, éléments structuraux
4. **Enveloppe Extérieure** - Toiture, revêtements, portes/fenêtres, structures extérieures
5. **Systèmes Mécaniques et Électriques** - Plomberie, électricité, CVAC
6. **Isolation et Étanchéité** - Isolation thermique, pare-vapeur, insonorisation
7. **Finitions Intérieures** - Gypse, peinture, portes, moulures, planchers
8. **Aménagements et Finitions Extérieures** - Entrée, terrassement, aménagement paysager

## Technologies

- **HTML5** - Structure sémantique
- **CSS3** - Styles responsive avec variables CSS
- **JavaScript ES6+** - Vanilla JS, aucune dépendance externe
- **LocalStorage** - Persistance des données côté client

## Installation

Aucune installation requise. L'application fonctionne directement dans un navigateur web moderne.

```bash
# Cloner le dépôt
git clone https://github.com/ConstructoAI/FORMULAIRE.git

# Ouvrir index.html dans un navigateur
```

## Utilisation

1. **Ouvrir** `index.html` dans un navigateur web
2. **Personnaliser** les informations de votre entreprise (en-tête)
3. **Ajouter un logo** en cliquant sur la zone prévue (optionnel)
4. **Remplir** les informations du client et du projet
5. **Entrer** les quantités et prix unitaires pour chaque item
6. **Ajuster** les taux (admin, contingence, profit) si nécessaire
7. **Sauvegarder** ou **Exporter** la soumission

### Raccourcis

| Bouton | Action |
|--------|--------|
| Sauvegarder | Sauvegarde la soumission dans le navigateur |
| Voir les soumissions | Liste des soumissions sauvegardées |
| Nouvelle soumission | Crée une nouvelle soumission vierge |
| Réinitialiser textes | Remet les textes par défaut |
| Réinitialiser montants | Remet tous les montants à zéro |
| Imprimer | Ouvre la boîte de dialogue d'impression |
| Exporter JSON | Télécharge les données en JSON |
| Importer JSON | Charge une soumission depuis un fichier JSON |
| Télécharger HTML | Télécharge une copie HTML autonome |

## Structure du projet

```
FORMULAIRE/
├── index.html      # Application complète (HTML + CSS + JS)
└── README.md       # Documentation
```

## Compatibilité

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Auteur

**Sylvain Leduc**

## Licence

© 2025 Constructo AI - Tous droits réservés

---

*Application développée pour le marché québécois de la construction résidentielle.*
