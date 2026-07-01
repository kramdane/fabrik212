# 06 — Référence Schemas JSON-LD — fabrik212.com
*Dernière mise à jour : juillet 2026*

Validation : https://validator.schema.org | https://search.google.com/test/rich-results

---

## 1. LocalBusiness (Master — à placer dans le `<head>` de index.html)

```json
{
  "@context": "https://schema.org",
  "@type": "MarketingAgency",
  "@id": "https://www.fabrik212.com/#organization",
  "name": "Fabrik212",
  "legalName": "Fabrik212",
  "url": "https://www.fabrik212.com",
  "logo": {
    "@type": "ImageObject",
    "url": "https://www.fabrik212.com/logo.svg",
    "width": 200,
    "height": 60
  },
  "image": "https://www.fabrik212.com/og-image.jpg",
  "description": "Fabrik212 est une agence marketing et web basée à Casablanca, Maroc. Nous proposons la création de sites internet, le SEO, Google Ads, et le marketing digital pour les entreprises marocaines.",
  "telephone": "+212XXXXXXXXX",
  "email": "contact@fabrik212.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "[Adresse complète]",
    "addressLocality": "Casablanca",
    "addressRegion": "Grand Casablanca-Settat",
    "postalCode": "[Code postal]",
    "addressCountry": "MA"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": 33.5731,
    "longitude": -7.5898
  },
  "openingHoursSpecification": [
    {
      "@type": "OpeningHoursSpecification",
      "dayOfWeek": ["Monday", "Tuesday", "Wednesday", "Thursday", "Friday"],
      "opens": "09:00",
      "closes": "18:00"
    }
  ],
  "contactPoint": {
    "@type": "ContactPoint",
    "telephone": "+212XXXXXXXXX",
    "contactType": "customer service",
    "availableLanguage": ["French", "Arabic"],
    "contactOption": "TollFree"
  },
  "sameAs": [
    "https://www.facebook.com/fabrik212",
    "https://www.instagram.com/fabrik212",
    "https://www.linkedin.com/company/fabrik212",
    "https://www.google.com/maps?cid=[VOTRE_CID_GBP]"
  ],
  "priceRange": "MAD MAD",
  "currenciesAccepted": "MAD",
  "paymentAccepted": "Virement, Chèque, Espèces",
  "areaServed": {
    "@type": "Country",
    "name": "Morocco"
  },
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "name": "Services Fabrik212",
    "itemListElement": [
      {
        "@type": "Offer",
        "itemOffered": {
          "@type": "Service",
          "name": "Création de site internet",
          "url": "https://www.fabrik212.com/creation-site-internet-maroc.html"
        }
      },
      {
        "@type": "Offer",
        "itemOffered": {
          "@type": "Service",
          "name": "SEO - Référencement Google",
          "url": "https://www.fabrik212.com/seo-maroc.html"
        }
      },
      {
        "@type": "Offer",
        "itemOffered": {
          "@type": "Service",
          "name": "Google Ads",
          "url": "https://www.fabrik212.com/google-ads-maroc.html"
        }
      }
    ]
  }
}
```

**Notes :**
- Remplacer `+212XXXXXXXXX` par le vrai numéro (URGENT — pas +32)
- Remplacer `[Adresse complète]` par l'adresse réelle
- Remplacer `[VOTRE_CID_GBP]` par le CID Google Business Profile (trouvable dans l'URL de la fiche GBP)
- `MarketingAgency` est un sous-type de `LocalBusiness` — parfait pour le cas Fabrik212

---

## 2. Service (à placer sur chaque page service)

### Template générique Service

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "[TYPE DE SERVICE]",
  "name": "[Nom du service]",
  "description": "[Description 150-300 chars]",
  "url": "https://www.fabrik212.com/[slug].html",
  "provider": {
    "@type": "MarketingAgency",
    "@id": "https://www.fabrik212.com/#organization"
  },
  "areaServed": {
    "@type": "Country",
    "name": "Morocco"
  },
  "offers": {
    "@type": "Offer",
    "priceCurrency": "MAD",
    "price": "[PRIX MIN]",
    "priceSpecification": {
      "@type": "PriceSpecification",
      "minPrice": "[PRIX MIN]",
      "maxPrice": "[PRIX MAX]",
      "priceCurrency": "MAD"
    },
    "description": "[Description de l'offre]"
  }
}
```

### Service — Création Site Internet

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Web Design",
  "name": "Création de site internet au Maroc",
  "description": "Création de sites web professionnels au Maroc : sites vitrines, e-commerce, applications web. Design moderne, mobile-first, optimisé SEO.",
  "url": "https://www.fabrik212.com/creation-site-internet-maroc.html",
  "provider": { "@type": "MarketingAgency", "@id": "https://www.fabrik212.com/#organization" },
  "areaServed": { "@type": "Country", "name": "Morocco" },
  "offers": {
    "@type": "Offer",
    "priceCurrency": "MAD",
    "priceSpecification": {
      "@type": "PriceSpecification",
      "minPrice": "1499",
      "maxPrice": "5000",
      "priceCurrency": "MAD"
    }
  }
}
```

### Service — SEO

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Search Engine Optimization",
  "name": "SEO et référencement Google au Maroc",
  "description": "Référencement naturel (SEO) au Maroc : audit, optimisation technique, création de contenu, netlinking. Suivi mensuel des positions Google.",
  "url": "https://www.fabrik212.com/seo-maroc.html",
  "provider": { "@type": "MarketingAgency", "@id": "https://www.fabrik212.com/#organization" },
  "areaServed": { "@type": "Country", "name": "Morocco" },
  "offers": {
    "@type": "Offer",
    "priceCurrency": "MAD",
    "priceSpecification": {
      "@type": "PriceSpecification",
      "minPrice": "1500",
      "priceCurrency": "MAD",
      "unitText": "par mois"
    }
  }
}
```

### Service — Google Ads

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "serviceType": "Online Advertising",
  "name": "Google Ads au Maroc",
  "description": "Gestion de campagnes Google Ads au Maroc : Search, Display, Shopping. Budget minimum 2 000 MAD/mois + 1 500 MAD de gestion mensuelle.",
  "url": "https://www.fabrik212.com/google-ads-maroc.html",
  "provider": { "@type": "MarketingAgency", "@id": "https://www.fabrik212.com/#organization" },
  "areaServed": { "@type": "Country", "name": "Morocco" },
  "offers": {
    "@type": "Offer",
    "priceCurrency": "MAD",
    "priceSpecification": {
      "@type": "PriceSpecification",
      "minPrice": "1500",
      "priceCurrency": "MAD",
      "description": "Frais de gestion mensuelle (hors budget publicitaire minimum 2 000 MAD)"
    }
  }
}
```

---

## 3. FAQPage (exemple générique)

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Combien coûte la création d'un site internet au Maroc ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "La création d'un site internet au Maroc coûte entre 1 499 MAD et 5 000+ MAD selon la complexité. Un site vitrine simple démarre à 1 499 MAD, un site e-commerce à partir de 3 500 MAD. Contactez-nous pour un devis personnalisé sur WhatsApp."
      }
    },
    {
      "@type": "Question",
      "name": "Combien de temps faut-il pour créer un site internet ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Le délai de création d'un site internet est de 1 à 3 semaines pour un site vitrine, et de 3 à 6 semaines pour un site e-commerce ou une application web plus complexe."
      }
    },
    {
      "@type": "Question",
      "name": "Proposez-vous le SEO en plus de la création de site ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui, nous proposons le SEO (référencement naturel Google) à partir de 1 500 MAD par mois, en complément ou indépendamment de la création de site. Un audit SEO initial est inclus."
      }
    },
    {
      "@type": "Question",
      "name": "Intervenez-vous dans toute la ville de Casablanca ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Oui, nous intervenons dans tous les quartiers de Casablanca (Maarif, Anfa, CFC, Sidi Maârouf, Ain Diab) ainsi que dans tout le Maroc. La plupart de nos échanges se font en ligne ou par WhatsApp."
      }
    },
    {
      "@type": "Question",
      "name": "Quel est le budget minimum pour Google Ads au Maroc ?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Le budget publicitaire minimum recommandé pour Google Ads au Maroc est de 2 000 MAD par mois. À cela s'ajoutent 1 500 MAD de frais de gestion mensuelle par Fabrik212."
      }
    }
  ]
}
```

**Règle** : placer le FAQPage schema en JSON-LD dans `<script type="application/ld+json">` — ne jamais l'injecter via microdata dans le HTML.

---

## 4. BreadcrumbList (patterns)

### Homepage
```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Accueil",
      "item": "https://www.fabrik212.com/"
    }
  ]
}
```

### Page service nationale
```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Accueil",
      "item": "https://www.fabrik212.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Création Site Internet Maroc",
      "item": "https://www.fabrik212.com/creation-site-internet-maroc.html"
    }
  ]
}
```

### Page service locale (3 niveaux)
```json
{
  "@context": "https://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [
    {
      "@type": "ListItem",
      "position": 1,
      "name": "Accueil",
      "item": "https://www.fabrik212.com/"
    },
    {
      "@type": "ListItem",
      "position": 2,
      "name": "Création Site Internet Maroc",
      "item": "https://www.fabrik212.com/creation-site-internet-maroc.html"
    },
    {
      "@type": "ListItem",
      "position": 3,
      "name": "Création Site Internet Casablanca",
      "item": "https://www.fabrik212.com/creation-site-internet-casablanca.html"
    }
  ]
}
```

---

## 5. Article (pour le blog)

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Combien coûte la création d'un site internet au Maroc en 2025 ?",
  "description": "Guide complet des tarifs de création de sites internet au Maroc : site vitrine, e-commerce, application web. Prix en MAD, délais et conseils.",
  "image": "https://www.fabrik212.com/blog/images/[slug]-og.jpg",
  "datePublished": "2025-01-15",
  "dateModified": "2026-06-30",
  "author": {
    "@type": "Organization",
    "name": "Fabrik212",
    "url": "https://www.fabrik212.com"
  },
  "publisher": {
    "@type": "Organization",
    "name": "Fabrik212",
    "logo": {
      "@type": "ImageObject",
      "url": "https://www.fabrik212.com/logo.svg"
    }
  },
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://www.fabrik212.com/blog/combien-coute-site-internet-maroc"
  },
  "keywords": "création site internet maroc, prix site web maroc, tarif site internet maroc",
  "articleSection": "Création Web",
  "inLanguage": "fr-MA"
}
```

---

## 6. WebSite avec SearchAction

```json
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "@id": "https://www.fabrik212.com/#website",
  "url": "https://www.fabrik212.com",
  "name": "Fabrik212 — Agence Marketing & Web Maroc",
  "description": "Agence marketing et web à Casablanca, Maroc. Création de sites internet, SEO, Google Ads, marketing digital.",
  "publisher": {
    "@type": "Organization",
    "@id": "https://www.fabrik212.com/#organization"
  },
  "inLanguage": "fr-MA",
  "potentialAction": {
    "@type": "SearchAction",
    "target": {
      "@type": "EntryPoint",
      "urlTemplate": "https://www.fabrik212.com/?s={search_term_string}"
    },
    "query-input": "required name=search_term_string"
  }
}
```

*Note : le SearchAction n'est utile que si le site a une fonction de recherche interne.*

---

## 7. Organisation

```json
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "@id": "https://www.fabrik212.com/#organization",
  "name": "Fabrik212",
  "url": "https://www.fabrik212.com",
  "logo": "https://www.fabrik212.com/logo.svg",
  "foundingDate": "[Année de création]",
  "founders": [
    {
      "@type": "Person",
      "name": "[Nom du fondateur]"
    }
  ],
  "numberOfEmployees": {
    "@type": "QuantitativeValue",
    "minValue": 1,
    "maxValue": 10
  },
  "knowsAbout": [
    "Marketing Digital",
    "Création de sites web",
    "SEO",
    "Google Ads",
    "Marketing Maroc"
  ],
  "areaServed": "MA",
  "contactPoint": {
    "@type": "ContactPoint",
    "contactType": "customer support",
    "telephone": "+212XXXXXXXXX",
    "availableLanguage": ["fr", "ar"]
  },
  "sameAs": [
    "https://www.facebook.com/fabrik212",
    "https://www.instagram.com/fabrik212",
    "https://www.linkedin.com/company/fabrik212"
  ]
}
```

---

## 8. Procédure de validation

### Étape 1 — Rich Results Test
URL : https://search.google.com/test/rich-results
- Tester : FAQPage, LocalBusiness, Article, BreadcrumbList

### Étape 2 — Schema.org Validator
URL : https://validator.schema.org
- Coller le JSON-LD ou l'URL de la page
- Vérifier : aucune erreur rouge, warnings jaunes tolérables

### Étape 3 — Google Search Console
- Aller dans "Améliorations" → voir les types de rich results détectés
- Après validation, soumission des URLs pour re-indexation

### Checklist de déploiement

- [ ] LocalBusiness sur index.html
- [ ] Service sur chaque page service (7 pages)
- [ ] FAQPage sur au moins 6 pages
- [ ] BreadcrumbList sur toutes les pages (sauf homepage)
- [ ] Article sur chaque article de blog
- [ ] WebSite sur index.html (1 fois)
- [ ] Organisation sur index.html (fusionnable avec LocalBusiness)
- [ ] Validation Rich Results Test : 0 erreur
- [ ] Validation Schema.org Validator : 0 erreur critique
