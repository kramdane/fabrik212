# 13 — Roadmap Implémentation 30-60-90 Jours — fabrik212.com

*Dernière mise à jour : juillet 2026*

---

## Mois 1 (J1-J30) — Fondations techniques et présence locale

### Semaine 1 (J1-J7) — Corrections critiques

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Remplacer numéro WhatsApp +32472241350 par +212XXXXXXXXX sur toutes les pages HTML | Dev | CRITIQUE | Signal local Maroc renforcé, crédibilité clients |
| Remplacer le numéro dans tous les schemas JSON-LD LocalBusiness | Dev | CRITIQUE | Cohérence NAP pour Google |
| Créer og-image.jpg (1200×630px) avec logo + tagline + "Casablanca, Maroc" | Design | HAUTE | CTR amélioré sur partages sociaux |
| Uploader og-image.jpg et vérifier que le lien og:image pointe dessus sur chaque page | Dev | HAUTE | Partages sociaux avec visuel |
| Vérifier/corriger l'email contact@dig.ma → contact@fabrik212.com dans les schemas | Dev | HAUTE | Cohérence marque |
| Tester la redirection 301 non-www vers www (curl -I http://fabrik212.com) | Dev | HAUTE | Éviter contenu dupliqué |

---

### Semaine 2 (J8-J14) — Sitemap et indexation

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Lister les 9 URLs de blog (blog/index.html + 8 articles) | Content | HAUTE | Préparation sitemap complet |
| Ajouter les 9 URLs blog dans sitemap.xml avec `<lastmod>` corrects | Dev | HAUTE | Indexation Google accélérée |
| Soumettre le sitemap mis à jour dans Google Search Console (GSC) | Marketing | HAUTE | Découverte pages blog par Google |
| Demander l'indexation manuelle des 9 pages dans GSC (Inspection d'URL) | Marketing | HAUTE | Indexation en 24-72h |
| Vérifier que robots.txt déclare bien `Sitemap: https://www.fabrik212.com/sitemap.xml` | Dev | MOYENNE | Crawlabilité |
| Ajouter width et height sur toutes les balises img (réduction CLS) | Dev | MOYENNE | Core Web Vitals |

---

### Semaine 3 (J15-J21) — Google Business Profile

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Créer ou revendiquer la fiche Google Business Profile | Marketing | CRITIQUE | Visibilité SEO local Casablanca |
| Renseigner le nom exact "Fabrik212" (vérifier cohérence NAP) | Marketing | CRITIQUE | Cohérence NAP |
| Sélectionner catégorie principale "Marketing Agency" + 3-4 catégories secondaires | Marketing | HAUTE | Apparition recherches sectorielles |
| Rédiger et ajouter la description optimisée 750 caractères (template section 2 du fichier 12) | Marketing | HAUTE | Visibilité et crédibilité |
| Ajouter les 10 services avec descriptions (template section 3 du fichier 12) | Marketing | HAUTE | Affichage dans "Services" GBP |
| Uploader minimum 10 photos (logo, couverture, équipe, réalisations) avec nommage SEO | Design | HAUTE | Confiance et visibilité |
| Créer le premier post GBP (template "Offre/Promotion" du fichier 12) | Marketing | MOYENNE | Activité de la fiche |
| Activer les attributs pertinents (langue, paiement, zone de service) | Marketing | MOYENNE | Filtres de recherche locale |
| Créer les 10 Q&A GBP préremplies (liste section 8 du fichier 12) | Marketing | MOYENNE | Réponses aux questions fréquentes |

---

### Semaine 4 (J22-J30) — Schemas et validation

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Valider tous les schemas JSON-LD sur validator.schema.org (0 erreur rouge) | Dev | HAUTE | Éligibilité rich results |
| Tester les FAQPage schemas sur Google Rich Results Test | Dev | HAUTE | Featured snippets Google |
| Corriger toutes les erreurs de schema identifiées | Dev | HAUTE | Rich results actifs |
| Vérifier les breadcrumbs sur les pages services | Dev | MOYENNE | Affichage breadcrumbs dans SERP |
| Soumettre les pages corrigées pour re-indexation dans GSC | Marketing | HAUTE | Prise en compte des corrections |
| Lancer PageSpeed Insights sur les 5 pages principales, noter les scores | Dev | MOYENNE | Baseline Core Web Vitals |
| Élargir les 2 titles trop courts (agence-web-maroc + agence-digitale-maroc) | Dev | BASSE | CTR Google légèrement amélioré |

---

## Mois 2 (J31-J60) — Contenu et Autorité

### Semaine 5 (J31-J37) — Blog articles 1-4

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Rédiger article 2.3 "Google Business Profile Maroc" (1 000-1 200 mots) | Content | HAUTE | Trafic informationnel, SEO local |
| Optimiser article 2.3 : meta, schema Article, FAQ 3 questions, CTA interne | Dev/Content | HAUTE | Indexation et rich results |
| Rédiger article 2.7 "Combien coûte le marketing digital au Maroc" (1 000 mots) | Content | HAUTE | Trafic informationnel qualifié |
| Optimiser article 2.7 et le lier vers agence-marketing-maroc.html | Dev/Content | HAUTE | Conversion |
| Publier les 2 articles et demander indexation dans GSC | Marketing | HAUTE | Présence dans Google sous 48h |
| Partager les 2 articles sur LinkedIn de l'entreprise | Marketing | MOYENNE | Backlinks sociaux, visibilité |
| Partager les 2 articles sur Instagram (story + post) | Marketing | MOYENNE | Trafic social |

---

### Semaine 6 (J38-J44) — Blog articles 5-8

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Rédiger article 2.5 "E-commerce Maroc paiement en ligne" | Content | HAUTE | Trafic qualifié e-commerce |
| Rédiger article 2.1 "Automatisation PME marocaines" | Content | HAUTE | Différenciation vs concurrents |
| Optimiser + publier les 2 articles avec schema Article et FAQPage | Dev/Content | HAUTE | Indexation Google |
| Ajouter les liens vers ces 4 nouveaux articles depuis les pages services correspondantes | Dev | HAUTE | Maillage interne renforcé |
| Soumettre les 4 URLs dans GSC | Marketing | HAUTE | Indexation rapide |
| Vérifier les pages existantes pour compléter les gaps identifiés dans le fichier 08 | Content | MOYENNE | Score complétude pages services |

---

### Semaine 7 (J45-J51) — Avis GBP et preuve sociale

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Identifier 10 anciens clients satisfaits à contacter | Commercial | HAUTE | Base pour demandes d'avis |
| Envoyer le message WhatsApp de demande d'avis (template fichier 12) aux 10 clients | Commercial | HAUTE | Objectif : 5 avis obtenus minimum |
| Répondre à TOUS les avis reçus (templates section 7 du fichier 12) | Marketing | HAUTE | Signaux d'activité GBP |
| Ajouter 3 témoignages clients sur la homepage (section à créer — fichier 07) | Design/Dev | HAUTE | Preuve sociale + conversion |
| Ajouter schema AggregateRating sur LocalBusiness | Dev | MOYENNE | Rich results étoiles dans SERP |
| Publier 2 posts GBP cette semaine | Marketing | MOYENNE | Activité de la fiche |

---

### Semaine 8 (J52-J60) — Analyse et optimisation

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Analyser GSC : quels articles captent du trafic déjà ? | Marketing | HAUTE | Prioriser l'optimisation |
| Identifier les pages avec CTR < 2% dans GSC | Marketing | HAUTE | Pages à optimiser en priorité |
| Réécrire les meta descriptions des pages CTR < 2% (si applicable) | Content | HAUTE | Amélioration CTR |
| Analyser les positions sur les keywords cibles (fichier 04) | Marketing | HAUTE | Mesure progression |
| Vérifier que les 10 articles de blog sont tous indexés dans GSC | Marketing | HAUTE | Couverture d'indexation |
| Publier post GBP "Étude de cas" cette semaine | Marketing | MOYENNE | Engagement fiche locale |
| S'inscrire sur Yabiladi Business et PagesJaunes Maroc (cohérence NAP) | Marketing | MOYENNE | Citations locales |

---

## Mois 3 (J61-J90) — Croissance et expansion

### Semaine 9 (J61-J67) — Articles Phase 2 (1-4)

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Rédiger article 2.2 "WordPress ou site sur mesure Maroc" | Content | HAUTE | Trafic comparatif qualifié |
| Rédiger article 2.6 "Marketing digital restaurants Casablanca" | Content | HAUTE | Trafic local sectoriel |
| Optimiser et publier les 2 articles avec schemas | Dev/Content | HAUTE | Indexation et maillage |
| Lier depuis les pages services correspondantes | Dev | HAUTE | Autorité pages piliers |
| Soumettre dans GSC + partager sur LinkedIn/Instagram | Marketing | HAUTE | Trafic initial |

---

### Semaine 10 (J68-J74) — Citations locales

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Créer ou vérifier fiche Kompass Maroc avec NAP identique | Marketing | HAUTE | Citation locale de référence |
| Créer fiche Cylex Maroc | Marketing | HAUTE | Citation locale |
| Créer profil Clutch.co (agences) avec portfolio | Marketing | HAUTE | Backlink qualifié + crédibilité |
| Vérifier cohérence NAP sur toutes les fiches créées | Marketing | CRITIQUE | Cohérence signaux locaux |
| Continuer publication posts GBP (1/semaine minimum) | Marketing | HAUTE | Activité constante |
| Rédiger articles 2.4 "SEO technique expliqué" et 2.8 "App mobile vs web" | Content | HAUTE | Diversification trafic |

---

### Semaine 11 (J75-J81) — Analyse trafic blog

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Analyser GA4 : quels articles génèrent le plus de trafic et conversions ? | Marketing | HAUTE | Identification des angles qui performent |
| Identifier les articles en position 5-15 sur GSC → optimisation possible | Marketing | HAUTE | Gains de position rapides |
| Optimiser les 2-3 articles les mieux positionnés (enrichir contenu, FAQ) | Content | HAUTE | Passage en top 3 |
| Analyser les mots-clés pour lesquels le site apparaît mais n'a pas de page dédiée | Marketing | MOYENNE | Identification pages à créer |
| Lancer la rédaction de l'article bonus de votre choix selon les données | Content | MOYENNE | Expansion thématique |
| Faire un bilan des avis GBP : nombre, note moyenne, réponses | Marketing | HAUTE | Santé fiche locale |

---

### Semaine 12 (J82-J90) — Décision Phase 2 et bilan

| Action | Responsable | Priorité | Impact attendu |
|---|---|---|---|
| Vérifier le trafic GSC depuis Rabat et Marrakech | Marketing | HAUTE | Décision création pages Rabat/Marrakech |
| Si trafic Rabat > 50 visites/mois → créer rabat.html | Dev/Content | HAUTE | Capture trafic régional |
| Si trafic Marrakech > 30 visites/mois → créer marrakech.html | Dev/Content | HAUTE | Capture trafic régional |
| Vérifier si seo-maroc.html est en position 11-20 → lancer seo-casablanca.html | Marketing | HAUTE | Renforcement SEO local |
| Vérifier si agence-web-maroc.html est en position 15+ → lancer agence-web-casablanca.html | Marketing | HAUTE | Renforcement local web |
| Compléter le bilan des 90 jours (tableau KPIs ci-dessous) | Marketing | HAUTE | Pilotage stratégique |
| Planifier les 3 prochains mois selon les données | Marketing | HAUTE | Continuité de la stratégie |

---

## KPIs à suivre — Tableau mensuel

| KPI | Outil | Mois 1 (baseline) | Mois 2 (cible) | Mois 3 (cible) |
|---|---|---|---|---|
| Impressions Google Search Console | GSC | À mesurer | +30% vs baseline | +60% vs baseline |
| Clics organiques totaux / mois | GSC | À mesurer | +25% vs baseline | +50% vs baseline |
| Position moyenne "agence marketing maroc" | GSC | À mesurer | < 20 | < 15 |
| Position moyenne "création site internet maroc" | GSC | À mesurer | < 15 | < 10 |
| Position moyenne "seo maroc" | GSC | À mesurer | < 20 | < 15 |
| CTR moyen site | GSC | À mesurer | > 3% | > 4% |
| Vues fiche GBP / mois | GBP Insights | À mesurer | +50% vs M1 | +100% vs M1 |
| Clics "Appeler" depuis GBP / mois | GBP Insights | À mesurer | 10+ | 20+ |
| Clics "Itinéraire" depuis GBP / mois | GBP Insights | À mesurer | 5+ | 10+ |
| Nombre d'avis GBP | GBP | 0-2 | 5+ | 10+ |
| Note moyenne GBP | GBP | - | 4,5+ | 4,7+ |
| Leads WhatsApp estimés (UTM) | GA4 / tracking | À mesurer | +20% vs M1 | +50% vs M1 |
| Pages blog indexées | GSC | 0/9 | 9/9 | 9/9 + 4 new |
| Score PageSpeed mobile (homepage) | PSI | À mesurer | > 75 | > 80 |

---

## Rappels systèmes de tracking à mettre en place avant J30

- [ ] Google Analytics 4 (GA4) installé et vérifié sur toutes les pages
- [ ] Google Search Console vérifié (propriété www.fabrik212.com)
- [ ] Liens WhatsApp trackés avec paramètres UTM : `?utm_source=site&utm_medium=cta&utm_campaign=whatsapp`
- [ ] Événement GA4 configuré pour les clics WhatsApp
- [ ] GBP relié à GSC pour les données de recherche locale
- [ ] Rapport GSC exporté en baseline J1 pour comparaison future
