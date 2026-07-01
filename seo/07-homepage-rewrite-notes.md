# 07 — Homepage Rewrite Notes — fabrik212.com

*Dernière mise à jour : juillet 2026*

---

## Ce qui a été fait (déjà en place)

### Bloc FAQ
- Section FAQ ajoutée avec 5 questions/réponses couvrant les intentions commerciales principales
- Schema FAQPage en JSON-LD déployé et validé sur validator.schema.org
- Questions ciblées : prix site web, délais, SEO, Google Ads, zones d'intervention

### Maillage interne renforcé
- Lien vers casablanca.html ajouté dans la section "Nos services à Casablanca"
- Lien vers etudes-de-cas.html ajouté dans la section preuve sociale (CTA "Voir nos réalisations")
- Les 7 pages services sont liées depuis la section services de la homepage

### Données structurées homepage
- Schema LocalBusiness / MarketingAgency présent
- Schema WebSite avec SearchAction présent
- Schema FAQPage présent
- BreadcrumbList non nécessaire sur la homepage (niveau racine)

---

## Ce qui reste à faire (par ordre de priorité)

### 1. Section Témoignages clients (HAUTE PRIORITÉ)

**Pourquoi :** La homepage manque de preuve sociale concrète. Les visiteurs qui arrivent pour la première fois ont besoin de validation avant de contacter.

**Contenu requis :** Minimum 3 témoignages avec :
- Prénom + initiale du nom ou nom complet si autorisé
- Secteur d'activité du client (restaurant, immobilier, e-commerce, etc.)
- Citation courte (2-4 phrases) centrée sur un résultat mesurable
- Photo du client (optionnelle mais recommandée pour la confiance)
- Note étoiles (optionnelle)

**Exemples de structure de témoignage :**
```
"Fabrik212 a créé notre site en 3 semaines et nous recevons maintenant
 5 demandes de devis par semaine via notre formulaire. Un investissement qui s'est
 rentabilisé dès le premier mois."
— Mehdi B., Gérant immobilier, Casablanca
```

**Schema à ajouter :** Review + AggregateRating sur le LocalBusiness.

---

### 2. Section "Pourquoi choisir Fabrik212 au Maroc" (MOYENNE PRIORITÉ)

**Pourquoi :** Différenciation par rapport aux concurrents. Les visiteurs comparent plusieurs agences.

**Contenu recommandé (wireframe):**

```
H2 : Pourquoi choisir Fabrik212 ?

[Icone] Expertise locale Maroc
Nous connaissons le marché marocain, les habitudes des consommateurs,
les modes de paiement locaux (CMI, virement, espèces). Pas une agence française
qui adapte ses templates.

[Icone] Tarifs transparents
Création de site dès 1 499 MAD. SEO dès 1 500 MAD/mois.
Google Ads dès 2 000 MAD de budget + 1 500 MAD de gestion. Sans surprise.

[Icone] Livraison rapide
Un site vitrine livré en 1 à 3 semaines. Réponse WhatsApp sous 2h en jours ouvrés.

[Icone] Résultats mesurables
Rapports mensuels de positionnement Google, statistiques de trafic,
rapport de campagnes Ads avec ROI clair.

[Icone] Support continu
Pas de relation one-shot. Nous suivons nos clients sur le long terme.
```

---

### 3. Renforcement du maillage local (MOYENNE PRIORITÉ)

**Liens à ajouter dans le corps de la homepage :**
- Mention de Casablanca avec lien vers casablanca.html dans le premier paragraphe
- Lien vers agence-marketing-casablanca.html dans la section "Nos services à Casablanca"
- Lien vers creation-site-internet-casablanca.html si mention des clients casablancais

---

### 4. Compteurs / chiffres clés (BASSE PRIORITÉ mais fort impact conversion)

**Proposition de section "Nos chiffres" :**
```
[X] sites créés     [X] clients satisfaits     [X] ans d'expérience     [X%] satisfaction
```
Ces chiffres renforcent la crédibilité et sont extractibles par les IA (GEO).

---

## Maquette texte — Sections à ajouter

### Section A : Témoignages (insérer après la section FAQ)

```
H2 : Ce que disent nos clients

[Card 1]
★★★★★
"[Citation client 1 — résultat mesurable]"
— [Prénom], [Secteur], Casablanca

[Card 2]
★★★★★
"[Citation client 2 — résultat mesurable]"
— [Prénom], [Secteur], Maroc

[Card 3]
★★★★★
"[Citation client 3 — résultat mesurable]"
— [Prénom], [Secteur], Casablanca

[Bouton] → Voir toutes nos études de cas
```

---

### Section B : Pourquoi Fabrik212

```
H2 : Pourquoi choisir Fabrik212 pour votre marketing digital au Maroc ?

[Grille 2×3 ou 3×2 de cards avec icône + titre + 2 lignes de texte]
```

---

### Section C : Chiffres clés (optionnel mais recommandé)

```
[4 compteurs animés]
15+ sites web livrés | 20+ clients actifs | 3 ans d'expérience | 98% satisfaction
```

---

## KPIs à surveiller post-déploiement

| KPI | Outil | Cible | Fréquence de suivi |
|---|---|---|---|
| CTR moyen sur la homepage (Google Search Console) | GSC | > 5% | Hebdomadaire |
| Position moyenne "agence marketing maroc" | GSC | Top 10 | Hebdomadaire |
| Temps moyen sur la page | GA4 | > 1min 30s | Mensuel |
| Taux de rebond | GA4 | < 60% | Mensuel |
| Clics WhatsApp depuis la homepage | GA4 Events | Augmentation mensuelle | Mensuel |
| Conversions formulaire | GA4 | Augmentation mensuelle | Mensuel |
| Impressions totales dans GSC | GSC | Croissance mensuelle | Mensuel |
