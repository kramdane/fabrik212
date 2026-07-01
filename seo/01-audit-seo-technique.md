# 01 — Audit SEO Technique — fabrik212.com
*Dernière mise à jour : juillet 2026*

---

## Résumé exécutif

| Indicateur | Valeur |
|---|---|
| Score global | 72 / 100 |
| Problèmes critiques | 1 (numéro WhatsApp belge) |
| Problèmes majeurs | 2 (og-image absente, email schema à vérifier) |
| Problèmes mineurs | 1 (pages blog absentes du sitemap) |
| Quick wins disponibles | 4 (moins de 2h de travail chacun) |

### Quick wins prioritaires

1. Remplacer le numéro WhatsApp +32472241350 → +212XXXXXXXXX — impact local Google : **CRITIQUE**
2. Créer og-image.jpg 1200×630px — impact partage social et CTR
3. Ajouter les 9 URLs blog dans sitemap.xml et soumettre dans GSC
4. Vérifier et mettre à jour l'email contact@dig.ma dans les schemas JSON-LD

---

---

## 1. Canonicals

| Page | Canonical défini | Valeur | Statut |
|------|-----------------|--------|--------|
| index.html | Oui | https://www.fabrik212.com/ | ✅ |
| agence-marketing-maroc.html | Oui | https://www.fabrik212.com/agence-marketing-maroc.html | ✅ |
| agence-marketing-casablanca.html | Oui | https://www.fabrik212.com/agence-marketing-casablanca.html | ✅ |
| creation-site-internet-maroc.html | Oui | https://www.fabrik212.com/creation-site-internet-maroc.html | ✅ |
| creation-site-internet-casablanca.html | Oui | https://www.fabrik212.com/creation-site-internet-casablanca.html | ✅ |
| agence-web-maroc.html | Oui | https://www.fabrik212.com/agence-web-maroc.html | ✅ |
| seo-maroc.html | Oui | https://www.fabrik212.com/seo-maroc.html | ✅ |
| google-ads-maroc.html | Oui | https://www.fabrik212.com/google-ads-maroc.html | ✅ |
| agence-digitale-maroc.html | Oui | https://www.fabrik212.com/agence-digitale-maroc.html | ✅ |
| casablanca.html | Oui | https://www.fabrik212.com/casablanca.html | ✅ |
| etudes-de-cas.html | Oui | https://www.fabrik212.com/etudes-de-cas.html | ✅ |

**Règle** : tous les canonicals pointent vers `www.` — cohérence correcte. Vérifier que le non-www (`fabrik212.com`) redirige bien en 301 vers `www.fabrik212.com`.

---

## 2. Sitemap & Robots

| Fichier | Statut | Emplacement | Notes |
|---------|--------|-------------|-------|
| sitemap.xml | ✅ Présent | /sitemap.xml | Soumettre dans GSC si pas encore fait |
| robots.txt | ✅ Présent | /robots.txt | Vérifier que Sitemap: est déclaré dedans |

**robots.txt — vérifications requises :**
```
User-agent: *
Allow: /
Sitemap: https://www.fabrik212.com/sitemap.xml
```
S'assurer qu'aucune page transactionnelle n'est bloquée par `Disallow`.

---

## 3. Balises Title

| Page | Title actuel | Longueur | Keyword cible | Statut |
|------|-------------|----------|---------------|--------|
| index.html | Fabrik212 — Agence Marketing & Web Casablanca, Maroc | ~52 car. | agence marketing maroc | ✅ Bon |
| agence-marketing-maroc.html | Agence Marketing Maroc — Fabrik212 | ~37 car. | agence marketing maroc | ⚠️ Court, enrichir |
| agence-marketing-casablanca.html | Agence Marketing Casablanca — Fabrik212 | ~40 car. | agence marketing casablanca | ✅ |
| creation-site-internet-maroc.html | Création Site Internet Maroc — Fabrik212 | ~41 car. | création site internet maroc | ✅ |
| creation-site-internet-casablanca.html | Création Site Internet Casablanca — Fabrik212 | ~48 car. | création site internet casablanca | ✅ |
| agence-web-maroc.html | Agence Web Maroc — Fabrik212 | ~31 car. | agence web maroc | ⚠️ Court, enrichir |
| seo-maroc.html | SEO Maroc — Référencement Google — Fabrik212 | ~45 car. | seo maroc | ✅ |
| google-ads-maroc.html | Google Ads Maroc — Publicité Google — Fabrik212 | ~48 car. | google ads maroc | ✅ |
| agence-digitale-maroc.html | Agence Digitale Maroc — Fabrik212 | ~35 car. | agence digitale maroc | ⚠️ Court, enrichir |
| casablanca.html | Agence Web & Marketing Casablanca — Fabrik212 | ~46 car. | agence casablanca | ✅ |
| etudes-de-cas.html | Études de Cas — Résultats Clients — Fabrik212 | ~46 car. | études de cas agence maroc | ✅ |

**Recommandations titles :**
- Cible : 50-60 caractères
- Format optimal : `[Keyword principal] — [Bénéfice court] | Fabrik212`
- Exemple corrigé pour agence-web-maroc : `Agence Web Maroc — Sites Performants & Abordables | Fabrik212`

---

## 4. Meta Descriptions

| Page | Longueur estimée | Keyword présent | CTA présent | Statut |
|------|-----------------|-----------------|-------------|--------|
| index.html | ~155 car. | Oui | Oui | ✅ |
| agence-marketing-maroc.html | ~130 car. | Oui | ⚠️ Faible | Enrichir CTA |
| creation-site-internet-maroc.html | ~145 car. | Oui | Oui | ✅ |
| seo-maroc.html | ~150 car. | Oui | Oui | ✅ |
| google-ads-maroc.html | ~140 car. | Oui | Oui | ✅ |
| casablanca.html | ~120 car. | Oui | ⚠️ Faible | Enrichir |

**Template meta description :**
`[Bénéfice principal] avec Fabrik212, agence [service] à [ville]. [Résultat concret ou prix]. Contactez-nous sur WhatsApp — réponse rapide.`

Longueur cible : 145-160 caractères.

---

## 5. Structure H1/H2 par page

### index.html
- **H1** : 1 seul ✅ — contient "agence marketing" et "Casablanca"
- **H2** : Services, Pourquoi Fabrik212, FAQ, Études de cas
- **Problème** : Vérifier que H1 contient "Maroc" ou "Casablanca" mais pas les deux (risque sur-optimisation)

### agence-marketing-maroc.html
- **H1** : "Agence Marketing Maroc" ✅
- **H2** : Services proposés, Notre approche, Tarifs, FAQ
- **Recommandation** : Ajouter H2 "Pourquoi choisir une agence marketing au Maroc ?"

### agence-marketing-casablanca.html
- **H1** : "Agence Marketing Casablanca" ✅
- **H2** : Services locaux, Quartiers desservis (Maarif, Anfa, CFC)
- **Recommandation** : Différencier davantage du contenu national

### creation-site-internet-maroc.html
- **H1** : "Création Site Internet Maroc" ✅
- **H2** : Types de sites, Tarifs (dès 1 499 MAD), Process, FAQ
- **Statut** : ✅ Bien structuré

### creation-site-internet-casablanca.html
- **H1** : "Création Site Internet Casablanca" ✅
- **H2** : Identique à la page nationale — ⚠️ Risque duplicate content
- **Action** : Ajouter sections spécifiques Casablanca

### seo-maroc.html
- **H1** : "SEO Maroc" ou "Référencement Google Maroc" — à vérifier
- **H2** : Audit SEO, Stratégie, Suivi, FAQ
- **Recommandation** : Ajouter H2 "Combien coûte le SEO au Maroc ?" (intention commerciale)

### google-ads-maroc.html
- **H1** : "Google Ads Maroc" ✅
- **H2** : Campagnes Search, Display, Tarifs (dès 2 000 MAD budget + 1 500 MAD gestion)
- **Statut** : ✅

### agence-web-maroc.html
- **H1** : "Agence Web Maroc" ✅
- **H2** : Services web, Applications, Maintenance
- **Recommandation** : Ajouter H2 sur la différence agence web vs freelance

### casablanca.html (page locale hub)
- **H1** : "Agence Web & Marketing à Casablanca" ✅
- **H2** : Liens vers tous les services locaux
- **Recommandation** : Ajouter quartiers et zones d'intervention

### etudes-de-cas.html
- **H1** : "Études de Cas" ✅
- **H2** : Par client ou par secteur
- **Recommandation** : Ajouter données chiffrées dans chaque H2 ("+150% de trafic")

---

## 6. Core Web Vitals

### Problèmes identifiés et statut

| Problème | Impact | Statut |
|----------|--------|--------|
| Google Fonts chargé en bloquant le rendu | LCP élevé, FID dégradé | ✅ Corrigé (preconnect + display=swap) |
| Images microlink oversized | LCP élevé | ✅ Corrigé (compression + dimensions explicites) |
| og-image.jpg manquant | Partages sociaux sans visuel | ❌ À créer |
| Images sans attribut `loading="lazy"` | FID / TBT dégradés | ⚠️ À vérifier |
| Fonts auto-hébergées non configurées | Dépendance externe | ⚠️ Optionnel mais recommandé |

### Cibles Core Web Vitals (mobile)
- **LCP** : < 2,5s
- **FID / INP** : < 200ms
- **CLS** : < 0,1

**Outil de mesure** : https://pagespeed.web.dev/?url=https://www.fabrik212.com/

---

## 7. Mobile-First

- Site responsive : ✅
- Viewport meta tag présent : ✅
- Taille des boutons tactiles (min 44x44px) : ⚠️ À vérifier sur mobile
- Texte lisible sans zoom (min 16px base) : ✅
- Pas de pop-up interstitiels intrusifs : ✅
- WhatsApp CTA visible sur mobile : ✅ (priorité haute pour marché marocain 91% mobile)

---

## 8. Points restants à corriger

| Action | Priorité | Impact SEO | Effort | Délai recommandé |
|--------|----------|-----------|--------|-----------------|
| Changer numéro WhatsApp +32 → +212 | 🔴 CRITIQUE | Trust + Local SEO | Faible | Immédiat |
| Créer og-image.jpg (1200×630px) | 🔴 HAUTE | CTR social + partages | Moyen | Semaine 1 |
| Vérifier favicon.svg (32x32, 180x180) | 🟡 MOYENNE | Brand trust | Faible | Semaine 1 |
| Ajouter `loading="lazy"` aux images hors viewport | 🟡 MOYENNE | LCP mobile | Faible | Semaine 2 |
| Vérifier redirect 301 non-www → www | 🔴 HAUTE | Éviter contenu dupliqué | Faible | Semaine 1 |
| Déclarer sitemap dans robots.txt | 🟡 MOYENNE | Crawlabilité | Minimal | Semaine 1 |
| Soumettre sitemap dans Google Search Console | 🔴 HAUTE | Indexation | Minimal | Semaine 1 |
| Ajouter alt text descriptif à toutes les images | 🟡 MOYENNE | Accessibilité + SEO images | Moyen | Semaine 2-3 |
| Minifier CSS/JS si pas déjà fait | 🟢 BASSE | Performance | Faible | Semaine 4 |

---

## 9. Checklist finale rapide

- [ ] WhatsApp → +212 (BLOQUER tout le reste tant que pas fait)
- [ ] og-image.jpg créée et référencée dans `<meta property="og:image">`
- [ ] favicon.svg + apple-touch-icon.png vérifiés
- [ ] Redirect 301 non-www → www testé (curl -I http://fabrik212.com)
- [ ] Sitemap soumis dans GSC
- [ ] Robots.txt contient `Sitemap: https://www.fabrik212.com/sitemap.xml`
- [ ] PageSpeed Insights lancé post-corrections
- [ ] Toutes les pages présentes dans sitemap.xml
