# Document Maître - Alignement Hypothèses & Validation
## TAG Heuer x IA - Pistes Réalistes

---

## 📱 PISTE D : ASSISTANT VENDEUR SUR IPAD
**Impact potentiel : +300k CHF/mois | Délai : 1-2 mois**

### Hypothèses à valider

| Hypothèse | Question de validation | Interlocuteur | Critère GO |
|-----------|----------------------|---------------|------------|
| **H1:** Les vendeurs perdent >10% de ventes faute d'infos sur le parcours digital client | "Combien de ventes perdues car vous ne savez pas ce que le client a vu online ?" | Vendeurs | >10% confirmé |
| **H2:** L'accès à l'historique web améliore la pertinence des recommandations | "Si vous aviez l'historique web sur iPad, qu'est-ce qui changerait dans la vente ?" | Vendeurs | Réponse concrète et enthousiaste |
| **H3:** Les vendeurs sont technophiles et prêts à adopter un iPad | "Sur 10, votre intérêt pour cet outil ?" | Vendeurs | Score ≥7/10 |
| **H4:** L'infrastructure permet une intégration simple | "Existe-t-il une API entre Salesforce et le système boutique ?" | Benoît | API existante |
| **H5:** Les vendeurs ont déjà des iPad/tablettes | "Les vendeurs ont des iPad en boutique aujourd'hui ?" | Benoît | Oui (sinon +30k€ équipement) |

### Données nécessaires pour le business case
- Nombre de vendeurs : _____
- Ventes moyennes/vendeur/mois : _____
- Temps moyen par vente : _____ min
- Taux de conversion boutique actuel : _____%

---

## 🎯 PISTE E : CRM PRÉDICTIF NEXT BEST ACTION
**Impact potentiel : +400k CHF/mois | Délai : 3-4 mois**

### Hypothèses à valider

| Hypothèse | Question de validation | Interlocuteur | Critère GO |
|-----------|----------------------|---------------|------------|
| **H1:** Salesforce Einstein est disponible sans surcoût | "Einstein est dans votre licence actuelle ?" | Benoît | Oui (sinon budget +50k) |
| **H2:** Le taux de conversion email est faible (<1%) avec marge de progression | "Taux de conversion actuel des emails ?" | Camille | <1% |
| **H3:** L'équipe marketing peut définir des actions différenciées par segment | "Si on prédit qu'un client achète dans 30j, quelle action spécifique ?" | Léa/Camille | Action claire et différenciée |
| **H4:** La segmentation actuelle est basique | "Combien de segments ? Critères ?" | Camille | <5 segments ou segmentation manuelle |
| **H5:** Les données sont suffisantes pour entraîner un modèle | "Nombre de clients avec historique d'achat ?" | Benoît/Camille | >10,000 clients |
| **H6:** Le tracking cross-canal existe | "Vous trackez le parcours web→boutique ?" | Léa | Tracking existant ou possible |

### Données nécessaires pour le business case
- Base clients active : _____ contacts
- Fréquence envoi emails : _____/mois
- Taux ouverture actuel : _____%
- Taux clic actuel : _____%
- Panier moyen suite email : _____ CHF

---

## ✉️ PISTE F : GÉNÉRATEUR NEWSLETTER IA
**Impact potentiel : +150k CHF/mois | Délai : 1 mois**

### Hypothèses à valider

| Hypothèse | Question de validation | Interlocuteur | Critère GO |
|-----------|----------------------|---------------|------------|
| **H1:** La création de newsletter prend >4h aujourd'hui | "Temps pour créer une newsletter complète ?" | Camille | >4 heures |
| **H2:** Le processus de validation reste simple avec plusieurs versions | "Si on génère 10 versions, qui valide et comment ?" | Camille | Process clair et rapide |
| **H3:** L'outil email a une API exploitable | "Mailchimp ou autre ? API disponible ?" | Benoît | API confirmée |
| **H4:** Le contenu généré par IA est acceptable pour le luxe | "Accepteriez-vous du contenu IA pour les newsletters ?" | Léa/Camille | Pas de blocage brand |
| **H5:** Les tests A/B sont possibles techniquement | "Faites-vous déjà des tests A/B ?" | Camille | Oui ou infrastructure prête |

### Données nécessaires pour le business case
- Nombre newsletters/mois : _____
- Coût actuel création (heures × taux) : _____ CHF
- Budget agence/freelance contenu : _____ CHF/an
- Taux ouverture à battre : _____%

---

## 🔄 QUESTIONS TRANSVERSALES (Pour tous)

### Validation du contexte général

| Question | Qui | Pourquoi c'est critique |
|----------|-----|------------------------|
| "Quel budget IA pour 2025 ?" | Benoît | Valider les 500k CHF nécessaires |
| "Le vrai problème prioritaire aujourd'hui ?" | Tous | Vérifier qu'on adresse le bon enjeu |
| "Qu'est-ce qui a foiré dans les POC précédents ?" | Benoît | Éviter de reproduire les erreurs |
| "Quelle initiative IA de la concurrence vous enviez ?" | Léa/Camille | Comprendre les attentes réelles |
| "Sur 10, la maturité data de TAG Heuer ?" | Benoît | Évaluer le réalisme des ambitions |

---

## 📊 MATRICE DE SCORING POST-ENTRETIENS

### Méthode de scoring (pour chaque piste)

| Critère | Poids | Score (0-3) | Note pondérée |
|---------|-------|-------------|---------------|
| **Faisabilité technique** | 30% | ___ | ___ |
| **Acceptance utilisateurs** | 25% | ___ | ___ |
| **Impact business** | 25% | ___ | ___ |
| **Rapidité déploiement** | 10% | ___ | ___ |
| **Risque faible** | 10% | ___ | ___ |
| **TOTAL** | 100% | | **___/3** |

**Règle de décision :**
- Score ≥2.5 → GO immédiat
- Score 2.0-2.5 → GO avec réserves
- Score 1.5-2.0 → Retravailler
- Score <1.5 → Abandon

---

## 🚨 RED FLAGS - ABANDON IMMÉDIAT SI...

### Pour iPad Vendeur
❌ Vendeurs score <5/10 d'intérêt
❌ Pas d'API Salesforce-Boutique ET délai >6 mois pour créer
❌ Résistance forte du management boutique

### Pour CRM Prédictif
❌ Einstein non disponible ET budget activation >100k
❌ Pas d'action marketing différenciée identifiée
❌ Base clients <5,000 (trop peu pour ML)

### Pour Newsletter IA
❌ Création actuelle <2h (pas assez d'économie)
❌ Process validation >5 personnes
❌ Refus catégorique contenu IA dans le luxe

---

## ✅ GREEN FLAGS - ACCÉLÉRER SI...

### Signaux très positifs
✅ Benoît : "On a déjà essayé, on sait faire"
✅ Vendeurs : "On en rêve depuis longtemps"
✅ Léa/Camille : "C'est notre priorité #1"
✅ Budget déjà alloué pour Q1 2025
✅ Concurrent l'a fait avec succès

---

## 📋 CHECKLIST FINALE DE COHÉRENCE

### Avant de recommander une piste, vérifier :

- [ ] Au moins 4/5 hypothèses validées
- [ ] Pas de red flag majeur
- [ ] Score pondéré ≥2.0
- [ ] Budget confirmé disponible
- [ ] Sponsor exécutif identifié
- [ ] Quick win possible en <3 mois
- [ ] ROI mesurable défini
- [ ] Pas de dépendance externe bloquante

### Règle d'or
> "Si on ne peut pas expliquer le ROI en 1 phrase simple, on ne fait pas."

---

## 📝 TEMPLATE DE SYNTHÈSE POST-ENTRETIENS

### Pour chaque piste retenue :

**[NOM DE LA PISTE]**
- ✅ Hypothèses validées : X/5
- 💰 ROI confirmé : _____ CHF/mois
- ⏱️ Délai réaliste : _____ mois
- 🎯 Sponsor : _____________
- ⚠️ Risque principal : _____________
- 🚀 Next step : _____________

### Recommandation finale :
**PISTE PRIORITAIRE :** _____________
**Pourquoi :** _____________
**Action immédiate :** _____________

---

*Document de travail - Validation terrain*
*Dernière mise à jour : 28/09/2025*
