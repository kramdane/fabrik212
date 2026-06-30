# SEO Issues — Priorités d'action
**Site :** fabrik212.com | **Date :** Juin 2026

---

## 🔴 PRIORITÉ 1 — Corriger immédiatement (bloquants)

### P1.1 — Canonical vers domaine mort
**Impact :** CRITIQUE — Google dirige toute l'autorité vers un domaine vide  
**Pages concernées :** Toutes (homepage + /agence-digitale-maroc.html)  
**Fix :**
```html
<!-- Sur homepage -->
<link rel="canonical" href="https://www.fabrik212.com/" />
<!-- Sur /agence-digitale-maroc.html -->
<link rel="canonical" href="https://www.fabrik212.com/agence-digitale-maroc.html" />
```
**Délai :** Immédiat (30 minutes de travail)

---

### P1.2 — Sitemap.xml manquant
**Impact :** CRITIQUE — Google ne découvre pas les nouvelles pages automatiquement  
**Fix :** Créer `/sitemap.xml` et soumettre dans Google Search Console  
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url><loc>https://www.fabrik212.com/</loc><priority>1.0</priority></url>
  <url><loc>https://www.fabrik212.com/agence-marketing-maroc.html</loc><priority>0.9</priority></url>
  <url><loc>https://www.fabrik212.com/agence-marketing-casablanca.html</loc><priority>0.9</priority></url>
  <url><loc>https://www.fabrik212.com/creation-site-internet-maroc.html</loc><priority>0.9</priority></url>
  <url><loc>https://www.fabrik212.com/creation-site-internet-casablanca.html</loc><priority>0.9</priority></url>
  <url><loc>https://www.fabrik212.com/agence-web-maroc.html</loc><priority>0.8</priority></url>
  <url><loc>https://www.fabrik212.com/seo-maroc.html</loc><priority>0.8</priority></url>
  <url><loc>https://www.fabrik212.com/google-ads-maroc.html</loc><priority>0.8</priority></url>
  <url><loc>https://www.fabrik212.com/agence-digitale-maroc.html</loc><priority>0.7</priority></url>
</urlset>
```
**Délai :** Immédiat

---

### P1.3 — Robots.txt manquant
**Impact :** HAUTE — Crawlers sans directive, risque de crawl inefficace  
**Fix :** Créer `/robots.txt` :
```
User-agent: *
Allow: /
Sitemap: https://www.fabrik212.com/sitemap.xml
```
**Délai :** Immédiat

---

### P1.4 — Architecture de pages inexistante (2 pages pour 6+ mots-clés)
**Impact :** CRITIQUE — Impossible de ranker sur des requêtes sans page dédiée  
**Fix :** Créer les 7 pages de l'architecture cible (voir arborescence-seo-v2.md)  
**Délai :** Semaine 1

---

## 🟠 PRIORITÉ 2 — Corriger dans la semaine

### P2.1 — H1 homepage sans mot-clé
**Impact :** HAUTE — Signal de pertinence manquant pour "agence marketing maroc"  
**Actuel :** "Votre présence digitale, sans compromis."  
**Suggestion :** Garder la tagline visuellement mais ajouter un H1 sémantique :
```html
<h1 class="sr-only">Agence Marketing & Web au Maroc — Fabrik212, Casablanca</h1>
<p class="hero-tagline">Votre présence digitale, <em>sans compromis.</em></p>
```
Ou reformuler le H1 visible pour inclure le mot-clé.  
**Délai :** 1 jour

---

### P2.2 — Title homepage trop long (66 car.)
**Actuel :** "Fabrik212 — Agence Digitale Maroc | Sites Web, Apps & Croissance" (66 car.)  
**Cible :** Max 60 caractères  
**Suggestion :** "Fabrik212 — Agence Marketing & Web au Maroc" (46 car.)  
**Délai :** 1 jour

---

### P2.3 — Title /agence-digitale-maroc.html trop long (65 car.)
**Actuel :** "Agence Digitale Maroc — Fabrik212 | Création Web, Apps & Croissance"  
**Suggestion :** "Agence Digitale Maroc | Fabrik212 — Casablanca" (48 car.)  
**Délai :** 1 jour

---

### P2.4 — Schema.org absent sur toutes les pages
**Impact :** HAUTE — Pas d'éligibilité aux rich results, invisible pour moteurs IA  
**Fix :** Implémenter Organization + LocalBusiness sur toutes les pages, FAQPage sur les pages avec FAQ, Service sur les pages services  
**Délai :** Semaine 1 (inclus dans création des nouvelles pages)

---

### P2.5 — OG tags absents sur /agence-digitale-maroc.html
**Fix :**
```html
<meta property="og:title" content="Agence Digitale Maroc | Fabrik212 — Casablanca">
<meta property="og:description" content="Fabrik212, agence digitale marocaine : création de sites web, applications, automatisation et conseil en croissance.">
<meta property="og:image" content="https://www.fabrik212.com/og-image.jpg">
<meta property="og:url" content="https://www.fabrik212.com/agence-digitale-maroc.html">
<meta property="og:type" content="article">
```
**Délai :** 1 jour

---

### P2.6 — Numéro WhatsApp belge (+32 472 241 350)
**Impact :** MOYENNE-HAUTE — Perte de confiance des prospects marocains  
**Fix :** Remplacer par numéro marocain (+212 6XX XXX XXX)  
**Note :** Si c'est intentionnel (fondateur basé en Belgique), ajouter une mention "Répondons depuis Casablanca & Europe" pour rassurer  
**Délai :** 1 jour

---

### P2.7 — Liens sociaux brisés (Instagram, LinkedIn = "#")
**Fix :** Ajouter les vraies URLs ou supprimer les liens  
**Délai :** 1 jour

---

## 🟡 PRIORITÉ 3 — Semaines 2-4

### P3.1 — Pas de portfolio indexable
**Fix :** Créer une page `/portfolio.html` avec études de cas (MySenseHub, Isamundo, Rankify + autres)  
Chaque projet = une section avec : défi, solution, résultats mesurables, lien vers le site.

### P3.2 — Pas de blog
**Fix :** Créer `/blog/` avec au minimum 4 articles initiaux :
- "Comment choisir une agence web à Casablanca en 2025"
- "Combien coûte un site web au Maroc ?"
- "SEO local au Maroc : guide complet pour PME"
- "Google Ads vs Meta Ads au Maroc : lequel choisir ?"

### P3.3 — Cannibalisation homepage vs /agence-digitale-maroc.html
**Fix :** Différencier clairement : homepage = corporate/notoriété, agence-digitale-maroc.html = contenu informatif/longue forme. Ajouter lien contextuel depuis la homepage vers la page longue forme.

### P3.4 — Hreflang manquant (si version arabe envisagée)
**Note :** Si création d'une version arabe du site envisagée, implémenter hreflang fr-MA / ar-MA.

### P3.5 — Balise meta keywords
**Fix :** Supprimer (balise ignorée par Google depuis 2009, peut signaler du spam)

---

## Plan de déploiement recommandé

| Semaine | Actions |
|---|---|
| Semaine 1 (J1-J2) | Corriger canonicals, créer robots.txt, créer sitemap.xml, fixer titles, fixer H1 |
| Semaine 1 (J3-J7) | Déployer les 7 nouvelles pages avec schema.org + soumettre sitemap GSC |
| Semaine 2 | Créer page portfolio, lier toutes les pages, fixer liens sociaux |
| Semaine 3-4 | Publier 4 premiers articles de blog, configurer GBP |
| Mois 2 | Monitoring rankings, ajustements, nouveaux contenus |
