# Proposition CACD2 — Assets

## Spline 3D (hero de `index.html`)

Le hero contient un placeholder CSS pour le visuel 3D (orbe iridescente animée). Pour intégrer la vraie scène Spline "Shape The Vibe" :

1. Ouvrir la scène dans Spline : https://app.spline.design/community/file/e754fa0f-f403-47be-8193-651b09ce1208
2. Exporter en lien public via Export → Web → Public URL
3. Remplacer dans `index.html` le bloc `<div class="hero__visual">` par :

```html
<iframe class="hero__visual"
        src="<URL_PUBLIC_SPLINE>"
        loading="lazy"
        title="Visuel 3D CACD2"></iframe>
```

4. Si nécessaire, retirer les `animation`, `filter` et `background` de `.hero__visual` dans `styles.css` (l'iframe portera le visuel)

Tag de remplacement dans le code : `<!-- @cacd2:spline-replace -->`

## Photos d'équipe

À ajouter dans `assets/team/` pour les versions futures (réutilisable dans templates content). Style cohérent avec l'existant : portraits éditoriaux type Welcome-to-the-Jungle, possibilité noir et blanc en accent.

## Logos clients & captures projets

Les case studies (Indosuez, LCL) utilisent actuellement des mockups CSS. Pour les versions client-facing, remplacer par les vraies captures d'écran avec autorisation. À placer dans `assets/cases/`.
