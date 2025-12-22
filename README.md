# website
Vitrine web pour les activités de Wesmaguhl et redirige vers leurs différents réseau.

## Utilisation de Cloudinary

Ce site utilise Cloudinary pour la gestion et l'optimisation des images :

- **Hébergement des images** : Toutes les images du site sont stockées sur Cloudinary
- **Optimisation automatique** : Cloudinary compresse et optimise automatiquement les images pour améliorer les performances
- **Transformation à la volée** : Les images peuvent être redimensionnées et transformées dynamiquement via les paramètres d'URL
- **Formats modernes** : Conversion automatique vers des formats optimisés (WebP, AVIF) selon le navigateur

### Configuration

Les URLs Cloudinary suivent ce format :
```
https://res.cloudinary.com/[cloud_name]/image/upload/[transformations]/[public_id]
```

### Exemples de transformations

- Redimensionnement : `w_800,h_600,c_fill`
- Qualité : `q_auto` (optimisation automatique)
- Format : `f_auto` (format automatique selon le navigateur)
