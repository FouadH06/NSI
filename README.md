# Luna Bites (Premium Redesign)

## Project Overview
Luna Bites is a fictional premium dessert café website designed as a complete static school project. The design revolves around a dark luxury theme inspired by moonlight, midnight cravings, elegant desserts, and premium café culture. This version has been significantly redesigned to offer a highly immersive, layered, and visually striking experience.

## Technologies Used
- HTML5 (Semantic Structure)
- CSS3 (Flexbox, CSS Grid, Custom Variables, Glassmorphism, Advanced Selectors)
- JavaScript (Vanilla JS for DOM manipulation, IntersectionObserver for animations)
- FontAwesome (for scalable vector icons)

## Design & Architecture
- **Theme Used:** Custom HTML/CSS theme called “Luna Bites (Premium Edition)”
- **Layout Chosen:** One-page restaurant landing page with a masonry gallery and split-layout forms.
- **Deployment Strategy:** Designed to be easily deployable on GitHub Pages or Vercel without a backend.

## Sections Included
1. **Header / Navigation:** Sticky top navigation with a glassmorphism blur effect and a mobile hamburger menu.
2. **Hero:** High-impact introduction with an eye-catching visual card, floating badges, and glowing background elements.
3. **Experience (Why Choose Us):** 4-column feature grid highlighting the café's core pillars with icons and hover effects.
4. **About:** A brief description of the café's concept and core features with split image/text layout.
5. **Menu:** Detailed dessert and drink offerings grouped by category, featuring thumbnails, tags (Best Seller, Chef's Pick), and pricing.
6. **Featured Product:** Highlighted signature dessert (Golden Caramel Cheesecake) with a detailed description list.
7. **Gallery:** A beautiful masonry grid showcasing the café's aesthetics with animated overlays on hover.
8. **Testimonials:** Fictional customer reviews to add realism, using star ratings and avatars.
9. **Contact / Reservation:** A split layout featuring business info (location, hours, contact) and a frontend reservation form with a JS-powered success message.
10. **Footer:** Enriched multi-column footer with fictional address, operating hours, social icons, and a newsletter form.

## Future Improvements
- Connect the reservation form and newsletter to a real backend database.
- Implement an online ordering system and shopping cart.
- Create an admin dashboard for menu management.

---

# Rapport de Projet NSI (Section en Français)

*Cette section est destinée à être copiée dans le rapport PDF final du projet.*

### Identité et URL
- **Nom, Prénom :** [Votre Nom et Prénom]
- **Classe :** [Votre Classe]
- **URL du site (Vercel/GitHub) :** [Insérer le lien de votre site déployé, ex: https://luna-bites.vercel.app]

### Thème et Layout
Le projet "Luna Bites" est un site vitrine "one-page" haut de gamme pour un café de desserts premium fictif ouvert de nuit. Suite à une refonte complète de son design, le thème "Dark Luxury" est désormais beaucoup plus immersif. Il utilise des effets de "glassmorphism" (verre dépoli), des arrière-plans superposés avec des halos lumineux, et un agencement en grille (dont une galerie de style *masonry*). Les couleurs sombres (noir profond et violet) contrastent avec des touches dorées (`#C9A44C`) pour donner un aspect élégant et moderne.

### Extensions / Outils utilisés
- **Éditeur de code :** Visual Studio Code (ou équivalent)
- **Langages :** HTML5, CSS3, JavaScript (Vanilla, sans framework)
- **Hébergement prévu :** GitHub (pour le contrôle de version) et Vercel (pour le déploiement continu).
- **Ressources externes :** Google Fonts (Playfair Display et Poppins), FontAwesome (pour la gestion des icônes vectorielles), Unsplash (pour les images de très haute qualité).

### Idées et Accroches
L'idée principale est de proposer une expérience "Instagrammable", vivante et très aboutie. L'ajout d'une section "Témoignages" et d'une section "Expérience" renforce le côté réaliste de la marque. Afin de rendre l'interface dynamique sans l'alourdir, j'ai implémenté une fonction de "Scroll Reveal" en JavaScript (utilisant l'API `IntersectionObserver`). Ainsi, les éléments de la page (textes, images, cartes de menu) apparaissent avec une animation fluide de fondu vers le haut ou vers les côtés lors du défilement de l'utilisateur.

### Améliorations non réalisées
Bien que le site paraisse terminé côté client (front-end), certaines fonctionnalités nécessiteraient un serveur (back-end) :
- Une véritable base de données (ex: SQL ou MongoDB) pour enregistrer les réservations et les inscriptions à la newsletter.
- Un système de commande en ligne complet (e-commerce).
- Un tableau de bord administrateur (CMS) permettant de modifier le menu ou la galerie d'images dynamiquement.

### Informations complémentaires
Le code a été pensé pour être propre, modulaire au niveau du CSS, et didactique. Le JavaScript est organisé de manière logique pour gérer le menu mobile, l'effet de flou sur le menu principal au scroll, les animations d'apparition au défilement, et la soumission du formulaire (qui empêche le rechargement de la page et affiche un message de succès). Le site est entièrement *responsive*, offrant une navigation optimale sur smartphones, tablettes et ordinateurs.
