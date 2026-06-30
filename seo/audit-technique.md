# Audit Technique SEO — fabrik212.com
**Date :** Juin 2026  
**Auditeur :** Lead SEO Technique  
**Périmètre :** fabrik212.com + fabrik212.ma

---

## 1. État des domaines

| Domaine | Statut | Canonical déclaré |
|---|---|---|
| fabrik212.com | ✅ Actif, redirige vers www.fabrik212.com | fabrik212.ma |
| www.fabrik212.com | ✅ Actif | fabrik212.ma |
| fabrik212.ma | ❌ MORT — retourne une page vide | — |
| www.fabrik212.ma | ❌ MORT | — |

**🚨 CRITIQUE — Canonical disaster :** Toute la page index.html et la page agence-digitale-maroc.html déclarent leur canonical vers `fabrik212.ma` — un domaine qui retourne une page vide. Google considère fabrik212.ma comme la version de référence, mais ne peut pas l'indexer. Cela signifie que **toute l'autorité SEO accumulée est dirigée vers un trou noir.**

---

## 2. Inventaire des URLs crawlées

| URL | Statut HTTP | Indexable | H1 présent | Title | Canonical | Schema.org |
|---|---|---|---|---|---|---|
| https://www.fabrik212.com/ | 200 | ✅ | ✅ | Fabrik212 — Agence Digitale Maroc \| Sites Web, Apps & Croissance | ❌ Pointe vers fabrik212.ma (mort) | ❌ Absent |
| https://www.fabrik212.com/agence-digitale-maroc.html | 200 | ✅ | ✅ | Agence Digitale Maroc — Fabrik212 \| Création Web, Apps & Croissance | ❌ Pointe vers fabrik212.ma (mort) | ❌ Absent |
| https://www.fabrik212.com/sitemap.xml | ❌ 404 | — | — | — | — | — |
| https://www.fabrik212.com/robots.txt | ❌ 404 | — | — | — | — | — |
| https://fabrik212.ma/ | ❌ Page vide | ❌ | ❌ | — | — | — |

**Total pages indexables réelles : 2**

---

## 3. Analyse On-Page

### Page : Homepage (/)

| Élément | Valeur | Statut |
|---|---|---|
| Title | "Fabrik212 — Agence Digitale Maroc \| Sites Web, Apps & Croissance" (66 car.) | ⚠️ Trop long (>60 car.) |
| Meta description | "Fabrik212 est une agence digitale marocaine spécialisée dans la création de sites web..." (157 car.) | ✅ Correct |
| H1 | "Votre présence digitale, sans compromis." | ❌ Aucun mot-clé cible |
| H2 | "Nos services", "Un process simple & efficace", "Ce qui nous distingue" | ⚠️ Pauvres en mots-clés |
| Mots-clés dans contenu | "agence digitale", "création de sites web", "Maroc" | ⚠️ Manque "marketing", "Casablanca" dans body |
| Images alt | Non vérifiable (SPA) | ⚠️ À vérifier |
| Liens internes | Navigation en ancres (#) uniquement — 0 lien vers agence-digitale-maroc.html dans le body | ❌ |
| Lien vers agence-digitale-maroc.html | Footer uniquement | ❌ |
| Schema.org | Absent | ❌ |
| Open Graph | ✅ Complet (og:title, og:description, og:image) | ✅ |
| Twitter Card | ✅ Present | ✅ |
| Robots meta | index, follow, max-snippet:-1 | ✅ |
| Langue | fr_MA | ✅ |
| Hreflang | Absent | ⚠️ |
| Vitesse perçue | Site SPA léger — estimé rapide | ✅ |

### Page : /agence-digitale-maroc.html

| Élément | Valeur | Statut |
|---|---|---|
| Title | "Agence Digitale Maroc — Fabrik212 \| Création Web, Apps & Croissance" (65 car.) | ⚠️ Trop long |
| Meta description | "Fabrik212, agence digitale marocaine : création de sites web, applications..." (155 car.) | ✅ |
| H1 | "Agence Digitale Maroc : Fabrik212, votre partenaire croissance" | ✅ Bon |
| H2 | "Le marché digital marocain en 2025", "Pourquoi choisir une agence digitale marocaine ?", "Nos services...", "Notre méthode de travail", "Questions fréquentes" | ✅ Bonne structure |
| Contenu | ~1 200 mots | ✅ Acceptable |
| FAQ | ✅ 5 questions | ✅ |
| Schema FAQPage | ❌ Absent | ❌ |
| Open Graph | ❌ Absent | ❌ |
| Twitter Card | ❌ Absent | ❌ |
| Lien retour homepage | ✅ (breadcrumb + logo) | ✅ |
| Lien depuis homepage | ❌ Footer seulement | ❌ |

---

## 4. Problèmes techniques critiques

### 🔴 CRITIQUE (à corriger immédiatement)

1. **Canonical mort** — Les deux pages pointent leur canonical vers `fabrik212.ma` qui est une page vide. Google ne peut pas crawler la version "référence" déclarée.
   - **Fix :** Changer tous les canonicals vers `https://www.fabrik212.com/[slug]`

2. **Sitemap.xml manquant** — Aucun sitemap sur .com ni sur .ma.
   - **Fix :** Créer `/sitemap.xml` listant toutes les URLs indexables.

3. **Robots.txt manquant** — Aucune directive pour les crawlers.
   - **Fix :** Créer `/robots.txt` avec `Sitemap:` pointant vers le sitemap.

4. **Seulement 2 pages indexables** — Pour cibler 6+ requêtes stratégiques, il faut 6+ pages dédiées.
   - **Fix :** Créer toutes les pages de l'architecture cible.

### 🟠 HAUTE PRIORITÉ

5. **Aucun schema.org** — Ni Organization, ni LocalBusiness, ni Service, ni FAQPage.
   - **Fix :** Implémenter sur toutes les pages.

6. **H1 homepage sans mot-clé** — "Votre présence digitale, sans compromis." est une tagline, pas un H1 SEO.
   - **Fix :** Intégrer le keyword principal dans le H1 ou utiliser une structure visuelle qui sépare tagline et H1 sémantique.

7. **Titles trop longs** — Homepage (66 car.) et agence-digitale-maroc.html (65 car.) dépassent 60 caractères.
   - **Fix :** Raccourcir à max 60 caractères.

8. **Open Graph manquant sur /agence-digitale-maroc.html** — Partage social sans prévisualisation.
   - **Fix :** Ajouter og:title, og:description, og:image.

9. **Numéro WhatsApp belge (+32 472...)** — Incohérence majeure pour une agence présentée comme marocaine. Perte de confiance et de conversions locales.
   - **Fix :** Utiliser un numéro marocain (+212) ou explication claire.

### 🟡 MOYEN

10. **Cannibalisation potentielle** — Homepage et /agence-digitale-maroc.html ciblent les mêmes requêtes sans différenciation claire.

11. **Liens sociaux brisés** — Instagram et LinkedIn pointent vers "#".

12. **Pas de pages localisation** — "Casablanca" n'a aucune page dédiée.

13. **Pas de blog** — Impossible de capter du trafic longue traîne.

14. **Pas de portfolio structuré** — Les 3 réalisations (MySenseHub, Isamundo, Rankify) ne sont pas des pages indexables.

15. **Meta keywords** — Balise obsolète mais inoffensive. Peut être retirée.

---

## 5. Performance et Core Web Vitals (estimation)

| Indicateur | Statut estimé | Commentaire |
|---|---|---|
| Mobile-first | ✅ | Déclaré et confirmé par le viewport meta |
| Images lazy load | ⚠️ À vérifier | SPA avec logo et images clients |
| JavaScript bloquant | ⚠️ Probable | SPA JavaScript-heavy |
| HTTPS | ✅ | Certificat SSL présent |
| Compression | ⚠️ À vérifier | |
| CDN | ⚠️ Inconnu | |
| PageSpeed Score | 🔄 À mesurer via PSI | Estim. 70-85 mobile |

**Recommandation :** Lancer un test PageSpeed Insights sur https://pagespeed.web.dev/ pour obtenir les métriques LCP, CLS, INP réelles.

---

## 6. Cannibalisation keyword

| Requête cible | Pages en compétition |
|---|---|
| "agence digitale maroc" | Homepage + /agence-digitale-maroc.html |
| "création site web maroc" | Homepage (mention) + /agence-digitale-maroc.html |
| "agence web casablanca" | Homepage (meta keywords) + /agence-digitale-maroc.html |

→ Risque de cannibalisation entre les 2 seules pages existantes sur les mêmes termes. À résoudre par une architecture avec pages dédiées.

---

## 7. Présence schema.org actuelle

**Résultat : 0 implémentation détectée.**

Aucun JSON-LD, aucun microdata, aucun RDFa sur les pages crawlées.

---

## 8. Résumé des scores

| Dimension | Score | Détail |
|---|---|---|
| Technique | 3/10 | Canonical mort, pas de sitemap, pas de robots.txt |
| On-Page | 4/10 | Quelques bonnes bases, mais H1 faible, titles trop longs |
| Contenu | 4/10 | Bon contenu sur /agence-digitale-maroc.html, mais seulement 2 pages |
| Autorité locale | 2/10 | Aucune page Casablanca, numéro non-marocain |
| Schema.org / AEO | 0/10 | Aucune implémentation |
| Architecture | 1/10 | 2 pages pour 6+ intentions de recherche cibles |
| **GLOBAL** | **2.3/10** | Potentiel énorme, base à reconstruire |
