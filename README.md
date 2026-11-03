# Diététique & Sport

Landing page Astro statique pour des consultations diététiques personnalisées.

## Base technique reprise

- Astro 5, rendu statique et déploiement GitHub Pages.
- Une page principale `src/pages/index.astro` avec sections narratives et responsive.
- Composant `src/components/ContactForm.astro` réutilisable, formulaire accessible et anti-spam.
- Animations légères via `IntersectionObserver`, avec prise en charge de `prefers-reduced-motion`.
- Endpoint de formulaire injecté par `PUBLIC_FORM_ENDPOINT`.

## Développement

```bash
npm install
npm run dev
npm run build
```

Dans GitHub, définir `PUBLIC_FORM_ENDPOINT` dans Settings → Secrets and variables → Actions → Variables avant de diffuser le formulaire.
