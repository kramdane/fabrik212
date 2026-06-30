# Checklist Post-Déploiement SEO
**Site :** fabrik212.com | **À utiliser après chaque déploiement de nouvelles pages**

---

## ✅ Étape 1 — Corrections techniques urgentes (J1)

- [ ] **Canonical corrigé** sur `index.html` → pointe vers `https://www.fabrik212.com/`
- [ ] **Canonical corrigé** sur `agence-digitale-maroc.html` → pointe vers son URL .com
- [ ] **robots.txt déployé** sur `https://www.fabrik212.com/robots.txt`
- [ ] **sitemap.xml déployé** sur `https://www.fabrik212.com/sitemap.xml`
- [ ] **Vérification HTTP 200** sur tous les fichiers : `curl -I https://www.fabrik212.com/robots.txt`
- [ ] **Canonical .ma résolu** : soit rediriger fabrik212.ma vers .com, soit supprimer le domaine .ma des canonicals

---

## ✅ Étape 2 — Google Search Console (J1)

- [ ] **Compte GSC créé** sur https://search.google.com/search-console
- [ ] **Propriété vérifiée** pour `www.fabrik212.com` (méthode : balise HTML ou DNS)
- [ ] **Sitemap soumis** dans GSC → Sitemaps → Entrer `sitemap.xml` → Soumettre
- [ ] **Inspection d'URL** lancée sur la homepage pour vérifier l'indexabilité
- [ ] **Demande d'indexation** soumise pour chaque nouvelle page via "Inspecter l'URL" → "Demander l'indexation"

---

## ✅ Étape 3 — Déploiement des nouvelles pages (J1-J7)

- [ ] `agence-marketing-maroc.html` déployée et accessible
- [ ] `agence-marketing-casablanca.html` déployée et accessible
- [ ] `creation-site-internet-maroc.html` déployée et accessible
- [ ] `creation-site-internet-casablanca.html` déployée et accessible
- [ ] `agence-web-maroc.html` déployée et accessible
- [ ] `seo-maroc.html` déployée et accessible
- [ ] `google-ads-maroc.html` déployée et accessible
- [ ] Chaque nouvelle page soumise à indexation dans GSC

---

## ✅ Étape 4 — Vérification On-Page sur chaque page (J1-J3)

Pour chaque nouvelle page, vérifier :
- [ ] **Title** entre 50 et 60 caractères
- [ ] **Meta description** entre 140 et 160 caractères
- [ ] **Un seul H1** par page, contenant le mot-clé principal
- [ ] **Canonical** correct (`https://www.fabrik212.com/[slug].html`)
- [ ] **Open Graph** présent (og:title, og:description, og:image, og:url)
- [ ] **Twitter Card** présent
- [ ] **Schema.org JSON-LD** valide (tester sur https://validator.schema.org/)
- [ ] **Breadcrumb** visible et schema présent
- [ ] **FAQPage schema** présent sur les pages avec FAQ
- [ ] **Liens internes** vers pages services liées (minimum 3 liens)
- [ ] **CTA WhatsApp** présent et lien fonctionnel
- [ ] **Robots meta** = index, follow

---

## ✅ Étape 5 — Test Schema.org (J1-J3)

- [ ] Tester chaque page sur https://validator.schema.org/
- [ ] Tester chaque page sur https://search.google.com/test/rich-results
- [ ] Vérifier absence d'erreurs sur : LocalBusiness, FAQPage, BreadcrumbList, Service
- [ ] Les FAQs sont éligibles aux rich snippets ✓ / Erreurs détectées : ___

---

## ✅ Étape 6 — Performance et mobile (J3-J7)

- [ ] **PageSpeed Insights** lancé sur chaque nouvelle page (https://pagespeed.web.dev/)
  - Homepage : Score mobile ___/100 | Score desktop ___/100
  - /agence-marketing-maroc : Score mobile ___/100
  - /creation-site-internet-maroc : Score mobile ___/100
- [ ] **Score mobile ≥ 80** sur toutes les pages (sinon optimiser images, lazy load, minification)
- [ ] **LCP (Largest Contentful Paint)** < 2.5s sur mobile
- [ ] **CLS (Cumulative Layout Shift)** < 0.1 sur mobile
- [ ] **Test mobile Google** : https://search.google.com/test/mobile-friendly
- [ ] Toutes les pages passent le test "Compatible mobile"

---

## ✅ Étape 7 — Maillage interne (J3-J7)

- [ ] **Homepage → /agence-marketing-maroc.html** : lien contextuel dans le body (pas juste footer)
- [ ] **Homepage → /creation-site-internet-maroc.html** : lien contextuel
- [ ] **Homepage → /agence-web-maroc.html** : lien contextuel
- [ ] **/agence-marketing-maroc → /agence-marketing-casablanca** : lien "version Casablanca"
- [ ] **/creation-site-internet-maroc → /creation-site-internet-casablanca** : lien version locale
- [ ] Chaque page service → /portfolio.html
- [ ] Navigation principale mise à jour avec les nouvelles pages
- [ ] Footer mis à jour avec toutes les pages

---

## ✅ Étape 8 — Google Business Profile (Semaine 1-2)

- [ ] Compte GBP créé ou revendiqué
- [ ] Vérification GBP complétée
- [ ] Nom, description, catégories remplis (voir recommandations-gbp.md)
- [ ] Logo + photo de couverture uploadés
- [ ] Au moins 5 photos de réalisations uploadées
- [ ] Services listés avec prix
- [ ] Q&A proactives créées (4 minimum)
- [ ] Numéro marocain (+212) utilisé — **pas le numéro belge**
- [ ] Lien vers site web = https://www.fabrik212.com

---

## ✅ Étape 9 — Liens sociaux (Semaine 1)

- [ ] **Instagram** : remplacer "#" par la vraie URL du profil Instagram
- [ ] **LinkedIn** : remplacer "#" par la vraie URL de la page LinkedIn
- [ ] **WhatsApp** : vérifier que le numéro est correct (envoyer un message test)
- [ ] **Email** contact@dig.ma : vérifier que les emails arrivent bien

---

## ✅ Étape 10 — Numéro de téléphone (Semaine 1)

- [ ] Remplacer `+32 472 241 350` (belgique) par numéro marocain `+212 6XX XXX XXX`
- [ ] Mettre à jour dans GBP
- [ ] Mettre à jour dans tous les `href="https://wa.me/..."` des pages HTML
- [ ] Vérifier cohérence sur toutes les pages

---

## ✅ Étape 11 — Soumission dans les annuaires locaux (Semaine 2-4)

Enregistrer Fabrik212 dans les annuaires locaux marocains pour la notoriété SEO :

- [ ] **Maroc.ma** : https://www.maroc.ma
- [ ] **Yabiladi** : section entreprises
- [ ] **Yellow Pages Maroc** : https://www.yellowpages.ma
- [ ] **Yelp Maroc** (si présent)
- [ ] **Facebook Page** : créer/mettre à jour la page entreprise avec URL site

---

## ✅ Étape 12 — Monitoring continu (Mensuel)

**Chaque mois, vérifier :**
- [ ] GSC → Performance → Positions moyennes sur les mots-clés cibles
- [ ] GSC → Couverture → Nouvelles erreurs d'indexation
- [ ] GSC → Core Web Vitals → Alertes
- [ ] Google Analytics (si installé) : trafic organique par page
- [ ] GBP Insights : vues, clics, appels
- [ ] Classement sur les 6 requêtes cibles (recherche manuelle en navigation privée au Maroc)

**Tableau de suivi des positions (à compléter mensuellement) :**

| Mot-clé cible | Position mois 1 | Mois 2 | Mois 3 | Mois 6 |
|---|---|---|---|---|
| agence marketing maroc | | | | |
| agence marketing casablanca | | | | |
| création site internet maroc | | | | |
| création site internet casablanca | | | | |
| agence web maroc | | | | |
| seo maroc | | | | |

---

## ✅ Étape 13 — Meta keywords à supprimer (J1)

La balise `<meta name="keywords">` est ignorée par Google depuis 2009 et peut signaler du contenu spam à certains moteurs. La supprimer de :
- [ ] `index.html`
- [ ] `agence-digitale-maroc.html`

---

## 🎯 Objectifs SEO à 3 mois

| Métrique | Objectif |
|---|---|
| Pages indexées dans GSC | 8+ |
| Position moyenne sur requêtes cibles | Top 20 |
| Trafic organique mensuel | +300 visiteurs |
| Position "agence marketing casablanca" | Top 10 |
| Avis GBP | 10+ (note ≥ 4.5) |
| Score PageSpeed mobile | 80+ sur toutes pages |

## 🎯 Objectifs SEO à 6 mois

| Métrique | Objectif |
|---|---|
| Position "agence marketing maroc" | Top 10 |
| Position "création site internet maroc" | Top 5 |
| Trafic organique mensuel | +1 000 visiteurs |
| Leads organiques/mois | 10+ |
| Apparitions dans Local Pack GBP | "agence marketing casablanca" |
