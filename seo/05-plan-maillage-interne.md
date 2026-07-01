# 05 — Plan de Maillage Interne — fabrik212.com
*Dernière mise à jour : juillet 2026*

---

## 1. Règles générales de maillage

### Hiérarchie des liens
1. **Pilier → Cluster** : une page pilier nationale lie obligatoirement vers ses variantes locales
2. **Cluster → Pilier** : la page locale mentionne et lie vers la page nationale (1-2 fois)
3. **Hub local → Services locaux** : casablanca.html lie vers toutes les pages /casablanca
4. **Blog → Transactionnel** : chaque article finit par un CTA avec lien vers 1 page service
5. **Études de cas → Services** : chaque cas client lie vers le service utilisé
6. **Services connexes → Services connexes** : SEO ↔ Google Ads, Web ↔ Marketing

### Densité recommandée
- Pages piliers : 4-6 liens internes sortants, 5+ liens entrants
- Pages clusters : 2-4 liens sortants, 3+ liens entrants
- Articles blog : 3-5 liens internes sortants, 1-2 liens entrants (depuis la page service associée)
- Homepage : 8-12 liens internes sortants vers toutes les sections

---

## 2. Tableau de maillage complet

### 2.1 Homepage → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| index.html | /agence-marketing-maroc.html | "agence marketing au Maroc" | Section services | 🔴 |
| index.html | /agence-marketing-casablanca.html | "agence marketing Casablanca" | Section services | 🔴 |
| index.html | /creation-site-internet-maroc.html | "création de site internet" | Section services | 🔴 |
| index.html | /agence-web-maroc.html | "agence web Maroc" | Section services | 🔴 |
| index.html | /seo-maroc.html | "référencement SEO" | Section services | 🔴 |
| index.html | /google-ads-maroc.html | "campagnes Google Ads" | Section services | 🟡 |
| index.html | /agence-digitale-maroc.html | "transformation digitale" | Section services | 🟡 |
| index.html | /casablanca.html | "notre agence à Casablanca" | Section localisation | 🟡 |
| index.html | /etudes-de-cas.html | "voir nos réalisations" | Section social proof | 🔴 |
| index.html | /etudes-de-cas.html | "études de cas clients" | CTA footer ou hero | 🔴 |

### 2.2 Agence Marketing Maroc → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /agence-marketing-maroc.html | /agence-marketing-casablanca.html | "agence marketing Casablanca" | Corps du texte | 🔴 |
| /agence-marketing-maroc.html | /seo-maroc.html | "référencement Google Maroc" | Section services inclus | 🔴 |
| /agence-marketing-maroc.html | /google-ads-maroc.html | "publicité Google Ads" | Section services inclus | 🔴 |
| /agence-marketing-maroc.html | /creation-site-internet-maroc.html | "création de site internet" | Section services inclus | 🟡 |
| /agence-marketing-maroc.html | /etudes-de-cas.html | "nos résultats concrets" | Section preuve sociale | 🟡 |
| /agence-marketing-maroc.html | / | "retour à l'accueil" | Breadcrumb | 🟢 |

### 2.3 Agence Marketing Casablanca → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /agence-marketing-casablanca.html | /agence-marketing-maroc.html | "notre agence marketing au Maroc" | Introduction | 🔴 |
| /agence-marketing-casablanca.html | /casablanca.html | "tous nos services à Casablanca" | Section locale | 🔴 |
| /agence-marketing-casablanca.html | /creation-site-internet-casablanca.html | "création de site à Casablanca" | Corps du texte | 🟡 |
| /agence-marketing-casablanca.html | /seo-maroc.html | "SEO et référencement" | Corps du texte | 🟡 |
| /agence-marketing-casablanca.html | /etudes-de-cas.html | "voir nos résultats" | CTA final | 🟡 |

### 2.4 Création Site Internet Maroc → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /creation-site-internet-maroc.html | /creation-site-internet-casablanca.html | "création de site à Casablanca" | Corps du texte | 🔴 |
| /creation-site-internet-maroc.html | /agence-web-maroc.html | "notre agence web" | Corps du texte | 🔴 |
| /creation-site-internet-maroc.html | /seo-maroc.html | "optimiser votre site pour Google" | Section SEO | 🟡 |
| /creation-site-internet-maroc.html | /etudes-de-cas.html | "exemples de sites créés" | Section portfolio | 🟡 |
| /creation-site-internet-maroc.html | / | "accueil Fabrik212" | Breadcrumb | 🟢 |

### 2.5 Création Site Internet Casablanca → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /creation-site-internet-casablanca.html | /creation-site-internet-maroc.html | "création site internet au Maroc" | Intro | 🔴 |
| /creation-site-internet-casablanca.html | /casablanca.html | "agence web Casablanca" | Corps | 🔴 |
| /creation-site-internet-casablanca.html | /agence-marketing-casablanca.html | "marketing digital Casablanca" | Section upsell | 🟡 |

### 2.6 Agence Web Maroc → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /agence-web-maroc.html | /creation-site-internet-maroc.html | "créer votre site internet" | Corps | 🔴 |
| /agence-web-maroc.html | /seo-maroc.html | "référencer votre site" | Corps | 🟡 |
| /agence-web-maroc.html | /agence-digitale-maroc.html | "transformation digitale complète" | Section avancée | 🟡 |
| /agence-web-maroc.html | /etudes-de-cas.html | "nos réalisations web" | Section portfolio | 🟡 |

### 2.7 SEO Maroc → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /seo-maroc.html | /google-ads-maroc.html | "compléter avec Google Ads" | Section comparaison | 🔴 |
| /seo-maroc.html | /creation-site-internet-maroc.html | "un site optimisé pour le SEO" | Intro | 🟡 |
| /seo-maroc.html | /agence-marketing-maroc.html | "stratégie marketing complète" | Corps | 🟡 |
| /seo-maroc.html | /etudes-de-cas.html | "résultats SEO obtenus" | Section preuve | 🟡 |

### 2.8 Google Ads Maroc → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /google-ads-maroc.html | /seo-maroc.html | "combiner SEO et Ads" | Section stratégie | 🔴 |
| /google-ads-maroc.html | /agence-marketing-maroc.html | "stratégie marketing globale" | Corps | 🟡 |
| /google-ads-maroc.html | /etudes-de-cas.html | "résultats de nos campagnes" | Section preuve | 🟡 |

### 2.9 Casablanca Hub → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /casablanca.html | /agence-marketing-casablanca.html | "marketing digital Casablanca" | Section services | 🔴 |
| /casablanca.html | /creation-site-internet-casablanca.html | "création site internet Casablanca" | Section services | 🔴 |
| /casablanca.html | /seo-maroc.html | "référencement SEO" | Section services | 🟡 |
| /casablanca.html | /google-ads-maroc.html | "publicité Google Ads" | Section services | 🟡 |
| /casablanca.html | /etudes-de-cas.html | "nos clients à Casablanca" | Section clients | 🟡 |

### 2.10 Études de cas → autres pages

| Page source | Page cible | Texte d'ancre | Emplacement | Priorité |
|-------------|------------|---------------|-------------|---------|
| /etudes-de-cas.html | /seo-maroc.html | "référencement SEO" | Pour chaque cas SEO | 🔴 |
| /etudes-de-cas.html | /creation-site-internet-maroc.html | "création de site" | Pour chaque cas web | 🔴 |
| /etudes-de-cas.html | /google-ads-maroc.html | "campagnes Google Ads" | Pour chaque cas Ads | 🟡 |
| /etudes-de-cas.html | / | "voir tous nos services" | CTA final | 🟡 |

---

## 3. Pages qui manquent de liens entrants

| Page | Liens entrants actuels (estimé) | Objectif | Action |
|------|--------------------------------|---------|--------|
| casablanca.html | 1-2 | 5+ | Ajouter dans menu nav ou footer + index.html |
| etudes-de-cas.html | 1-2 | 6+ | Ajouter CTA sur toutes les pages services |
| google-ads-maroc.html | 2-3 | 4+ | Lier depuis seo-maroc.html et agence-marketing-maroc.html |
| agence-digitale-maroc.html | 1-2 | 4+ | Lier depuis index.html et agence-web-maroc.html |
| Articles de blog | 0-1 | 3+ | Lier depuis page service correspondante |

---

## 4. Textes d'ancre — à utiliser et éviter

### Textes d'ancre recommandés (naturels et variés)

| Service | Ancres primaires | Ancres secondaires | Ancres génériques |
|---------|-----------------|-------------------|-------------------|
| Agence marketing | "agence marketing Maroc", "marketing digital Maroc" | "notre agence", "stratégie marketing" | "en savoir plus" |
| Création site | "création de site internet", "site web professionnel" | "notre service web", "sites réalisés" | "découvrir" |
| SEO | "référencement SEO", "SEO au Maroc" | "positionnement Google", "optimisation" | "notre approche SEO" |
| Google Ads | "Google Ads Maroc", "publicité Google" | "campagnes payantes", "Ads" | "en savoir plus" |
| Casablanca | "Casablanca", "notre agence à Casablanca" | "services locaux", "Maarif" | "ici" |

### Textes d'ancre à éviter (sur-optimisation)

- "cliquez ici", "ici", "lien" (trop générique, 0 valeur SEO)
- Répéter le même texte exact 5+ fois (risque over-optimisation)
- Keyword stuffing dans l'ancre : "meilleure agence marketing digital casablanca maroc pas cher"
- Ancres sans contexte dans des listes à puces isolées

---

## 5. Intégration dans le footer (liens permanents)

```
Footer recommandé :
- Accueil
- Agence Marketing Maroc
- Création Site Internet Maroc
- SEO Maroc
- Google Ads Maroc
- Agence Web Maroc
- Casablanca (page locale hub)
- Études de Cas
- Contact / WhatsApp
```

Le footer est la façon la plus simple d'assurer que chaque page reçoit au minimum 1 lien interne depuis toutes les autres pages.
