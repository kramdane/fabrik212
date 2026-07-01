# 03 — Arborescence SEO Finale — fabrik212.com
*Dernière mise à jour : juillet 2026*

---

## 1. Arborescence visuelle

```
fabrik212.com/
│
├── index.html                              [PILIER HOMEPAGE]
│   ├── agence-marketing-maroc.html         [PILIER — Marketing National]
│   │   └── agence-marketing-casablanca.html [CLUSTER — Marketing Local]
│   │
│   ├── creation-site-internet-maroc.html   [PILIER — Web National]
│   │   └── creation-site-internet-casablanca.html [CLUSTER — Web Local]
│   │
│   ├── agence-web-maroc.html               [PILIER — Agence Web]
│   │
│   ├── seo-maroc.html                      [PILIER — SEO National]
│   │   └── [Phase 2] seo-casablanca.html   [CLUSTER — SEO Local]
│   │
│   ├── google-ads-maroc.html               [PILIER — Paid Ads]
│   │
│   ├── agence-digitale-maroc.html          [PILIER — Digital Global]
│   │
│   ├── casablanca.html                     [HUB LOCAL — Casablanca]
│   │   ├── agence-marketing-casablanca.html
│   │   ├── creation-site-internet-casablanca.html
│   │   └── [Phase 2] agence-web-casablanca.html
│   │
│   ├── etudes-de-cas.html                  [PREUVE SOCIALE]
│   │
│   └── blog/                               [CLUSTER BLOG — Phase 1-2]
│       ├── [Article 1 — créé]
│       ├── [Article 2 — créé]
│       ├── [Article 3 — créé]
│       ├── [Article 4 — créé]
│       ├── [Article 5 — créé]
│       ├── [Article 6 — créé]
│       ├── [Article 7 — créé]
│       ├── [Article 8 — créé]
│       └── [Articles 9-16 — Phase 2]
│
├── sitemap.xml
└── robots.txt
```

---

## 2. Tableau complet des pages existantes

| Page | URL | Keyword principal | Intention | Type | Silo | Priorité |
|------|-----|-------------------|-----------|------|------|----------|
| Homepage | / | agence marketing maroc | Navigational + Commercial | Pilier | Global | 1 |
| Agence Marketing Maroc | /agence-marketing-maroc.html | agence marketing maroc | Commercial | Pilier | Marketing | 1 |
| Agence Marketing Casablanca | /agence-marketing-casablanca.html | agence marketing casablanca | Commercial Local | Cluster | Marketing Local | 1 |
| Création Site Internet Maroc | /creation-site-internet-maroc.html | création site internet maroc | Commercial | Pilier | Web | 1 |
| Création Site Internet Casablanca | /creation-site-internet-casablanca.html | création site internet casablanca | Commercial Local | Cluster | Web Local | 1 |
| Agence Web Maroc | /agence-web-maroc.html | agence web maroc | Commercial | Pilier | Web | 1 |
| SEO Maroc | /seo-maroc.html | seo maroc | Commercial + Info | Pilier | SEO | 1 |
| Google Ads Maroc | /google-ads-maroc.html | google ads maroc | Commercial | Pilier | Ads | 2 |
| Agence Digitale Maroc | /agence-digitale-maroc.html | agence digitale maroc | Commercial | Pilier | Digital | 2 |
| Casablanca Hub | /casablanca.html | agence casablanca | Local | Hub | Local | 2 |
| Études de cas | /etudes-de-cas.html | résultats agence marketing maroc | Transactionnel | Preuve | Global | 2 |

---

## 3. Siloing thématique

### Silo 1 — Marketing
```
Pilier : agence-marketing-maroc.html
  └── Cluster local : agence-marketing-casablanca.html
  └── Blog support : "Comment faire du marketing digital au Maroc ?"
  └── Blog support : "Marketing digital vs traditionnel au Maroc"
```

### Silo 2 — Web & Développement
```
Pilier A : agence-web-maroc.html
Pilier B : creation-site-internet-maroc.html
  └── Cluster local : creation-site-internet-casablanca.html
  └── Blog support : "Combien coûte un site internet au Maroc ?"
  └── Blog support : "Site vitrine vs e-commerce : quoi choisir ?"
  └── [Phase 2] Cluster local : agence-web-casablanca.html
```

### Silo 3 — SEO & Visibilité
```
Pilier : seo-maroc.html
  └── [Phase 2] Cluster local : seo-casablanca.html
  └── Blog support : "SEO ou Google Ads : que choisir au Maroc ?"
  └── Blog support : "Combien de temps pour référencer son site ?"
```

### Silo 4 — Publicité Payante
```
Pilier : google-ads-maroc.html
  └── Blog support : "Comment créer une campagne Google Ads au Maroc"
  └── Blog support : "Quel budget Google Ads pour une PME marocaine ?"
```

### Silo 5 — Local Casablanca
```
Hub : casablanca.html
  └── agence-marketing-casablanca.html
  └── creation-site-internet-casablanca.html
  └── [Phase 2] seo-casablanca.html
  └── [Phase 2] agence-web-casablanca.html
```

---

## 4. Règles de maillage interne (rappel)

- **Pilier → Cluster** : chaque pilier lie vers ses clusters locaux dans le corps du texte
- **Cluster → Pilier** : les clusters remontent vers le pilier national (1-2 liens)
- **Hub local → tous services locaux** : casablanca.html lie vers toutes les pages casablanca
- **Blog → Transactionnel** : chaque article de blog lie vers 1-2 pages de services
- **Études de cas → Services** : etudes-de-cas.html lie vers les services utilisés dans chaque cas
- **Pas de liens entre piliers concurrents** : eviter de diluer l'autorité entre agence-web et agence-marketing

---

## 5. Pages orphelines à éviter

**Règle** : toute page doit recevoir au minimum 2 liens internes depuis d'autres pages.

| Page à risque d'orphelinage | Solution |
|----------------------------|---------|
| casablanca.html | Lier depuis index.html + agence-marketing-casablanca.html |
| etudes-de-cas.html | Lier depuis index.html + toutes pages services |
| google-ads-maroc.html | Lier depuis seo-maroc.html + agence-marketing-maroc.html |
| agence-digitale-maroc.html | Lier depuis index.html + agence-marketing-maroc.html |
| Articles de blog | Lier depuis la page service associée (catégorie ou mention) |

---

## 6. Pages à créer — Phase 2

### Pages locales prioritaires

| Page | URL cible | Keyword | Condition de création |
|------|-----------|---------|----------------------|
| SEO Casablanca | /seo-casablanca.html | seo casablanca | Dès que seo-maroc.html > position 10 |
| Agence Web Casablanca | /agence-web-casablanca.html | agence web casablanca | Dès que agence-web-maroc.html > position 15 |
| Agence Marketing Rabat | /rabat.html | agence marketing rabat | Si trafic GSC de Rabat > 50/mois |
| Agence Marketing Marrakech | /marrakech.html | agence marketing marrakech | Si trafic GSC de Marrakech > 30/mois |

### Pages ressources

| Page | URL cible | Objectif |
|------|-----------|---------|
| Tarifs | /tarifs.html | Capter l'intention "prix" + faciliter la conversion |
| À propos | /a-propos.html | E-E-A-T, trust, lier vers équipe |
| Contact | /contact.html | Conversion + NAP cohérence |

### Extensions blog (Phase 2)

| Sujet | URL cible | Silo |
|-------|-----------|------|
| "Application web vs site internet" | /blog/application-web-vs-site-internet | Web |
| "Automatisation marketing Maroc" | /blog/automatisation-marketing-maroc | Digital |
| "E-commerce au Maroc : guide 2025" | /blog/ecommerce-maroc-guide | Web |
| "Réseaux sociaux pour entreprises marocaines" | /blog/reseaux-sociaux-entreprises-maroc | Marketing |
| "Comment mesurer le ROI de son marketing digital" | /blog/roi-marketing-digital-maroc | Marketing |
| "WhatsApp Business pour PME marocaines" | /blog/whatsapp-business-pme-maroc | Marketing |
| "Choisir un nom de domaine .ma" | /blog/nom-de-domaine-ma-maroc | Web |
| "Hébergement web au Maroc : comparatif" | /blog/hebergement-web-maroc | Web |

---

## 7. Vérifications d'architecture

- [ ] Toutes les pages sont dans sitemap.xml
- [ ] Aucune page n'a de canonical vers une URL différente de la sienne (sauf redirections voulues)
- [ ] Chaque page service reçoit au moins 2 liens internes
- [ ] casablanca.html est accessible depuis le menu ou le footer
- [ ] etudes-de-cas.html est accessible depuis la homepage
- [ ] Aucune page en `noindex` par erreur dans les meta ou robots.txt
