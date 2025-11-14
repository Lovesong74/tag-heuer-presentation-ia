# Guide d'Entretien - Validation Pistes IA TAG Heuer
## Objectif : Valider ou tuer 3 pistes en 1h20

---

## 📋 CONTEXTE RAPIDE

**3 Pistes à valider :**
1. **iPad Vendeur** : Historique client sur tablette (+300k CHF/mois potentiel)
2. **CRM Prédictif** : Salesforce Einstein pour Next Best Action (+400k CHF/mois potentiel)
3. **Newsletter IA** : Génération et personnalisation automatique (+150k CHF/mois potentiel)

**Timing total : 1h20**
- 30 min : Benoît (IT/IA)
- 20 min : Vendeurs boutique
- 15 min : Léa (Digital)
- 15 min : Camille (CRM)

---

## 🤖 ENTRETIEN 1 : BENOÎT (Responsable IT/IA)
**Durée : 30 minutes max**

### Introduction (1 min)
> "On a 30 minutes. On veut valider 3 quick wins IA réalistes, implémentables en 3 mois avec ROI immédiat. Pas de transformation lourde, que du pragmatique."

### Questions Infrastructure (5 min)

| Question | Réponse attendue | Si "Non" → Action |
|----------|-----------------|-------------------|
| 1. **Salesforce Einstein est dans votre licence actuelle ?** | Oui/Non | Non = Vérifier coût activation |
| 2. **Les vendeurs ont des iPad/tablettes en boutique ?** | Oui/Non + Quelle app | Non = Coût équipement à ajouter |
| 3. **Vous avez une API Salesforce ↔ Système boutique ?** | Oui/Non | Non = Complexité++ pour iPad |
| 4. **Outil newsletters actuel ? (Mailchimp, autre ?)** | Nom + API dispo | Pas d'API = Abandon Newsletter IA |

### Questions Blocages (5 min)

5. **Le POC chatbot customer care - pourquoi ça n'a pas marché ?**
   - Noter les erreurs à éviter
   
6. **Votre plus gros problème data aujourd'hui en une phrase ?**
   - Identifier le risque principal

### Questions Faisabilité (10 min)

7. **Pour l'iPad vendeur - délai réaliste ?**
   - [ ] < 2 mois → GO
   - [ ] 2-6 mois → Maybe
   - [ ] > 6 mois → NO GO

8. **Pour activer Einstein - complexité de 1 à 10 ?**
   - [ ] 1-3 → GO
   - [ ] 4-6 → Maybe  
   - [ ] 7-10 → NO GO

9. **Pour connecter GPT-4 aux newsletters - bloqueurs ?**
   - Lister et évaluer criticité

### Test de Réalité (5 min)

10. **Avec 150k CHF et 3 mois, laquelle des 3 pistes vous feriez ?**
    - Noter sa préférence et pourquoi

---

## 🏪 ENTRETIEN 2 : VENDEURS BOUTIQUE
**Durée : 20 minutes max**

### Introduction (1 min)
> "On teste des outils pour vous faciliter la vente. Vos retours honnêtes sont cruciaux. Pas de bonne ou mauvaise réponse."

### Questions Réalité Terrain (10 min)

| Question | Seuil de validation |
|----------|-------------------|
| 1. **Vous perdez combien de ventes car vous ne savez pas ce que le client a vu online ?** | > 10% = Opportunité |
| 2. **Temps perdu à chercher des infos pendant une vente ?** | > 5 min = Problème à résoudre |
| 3. **Comment vous checkez le stock autres boutiques ?** | Manuel = Opportunité automatisation |

### Test d'Acceptation iPad (5 min)

4. **Sur 10, votre intérêt pour avoir l'historique web du client sur iPad ?**
   - [ ] 8-10 → GO
   - [ ] 5-7 → Formation nécessaire
   - [ ] < 5 → NO GO

5. **Qu'est-ce qui vous ferait dire "NON" à cet iPad ?**
   - Identifier les freins

### Question Ouverte (4 min)

6. **Votre plus grosse frustration en vendant ?**
   - Voir si nos pistes répondent au vrai problème

---

## 💻 ENTRETIEN 3 : LÉA (Digital Experience Manager)
**Durée : 15 minutes max**

### Introduction (30 sec)
> "15 minutes pour valider des données clés sur le parcours web-to-store et les quick wins potentiels."

### Baseline Metrics (5 min)

| Métrique | Valeur | Impact pour nous |
|----------|--------|-----------------|
| 1. **Taux conversion web actuel ?** | ___% | Base pour calculer gains |
| 2. **Sessions moyennes avant achat ?** | ___ | Complexité parcours |
| 3. **Abandons panier/mois ?** | ___ | Volume à retravailler |

### Questions Tracking (5 min)

4. **Vous trackez web → boutique comment ?**
   - [ ] Pas du tout → Opportunité
   - [ ] Manuellement → Automatisation possible
   - [ ] Automatisé → Données disponibles

5. **Cookie matching existe ?**
   - Oui/Non → Faisabilité cross-canal

### Test Valeur (4 min)

6. **Si on prédit qui achète dans 30 jours, votre action #1 ?**
   - Action claire = GO
   - Flou = Retravailler le use case

---

## 📧 ENTRETIEN 4 : CAMILLE (Client Development & CRM)
**Durée : 15 minutes max**

### Introduction (30 sec)
> "Focus sur l'optimisation CRM et newsletters. Besoin de benchmarks actuels."

### Performance Actuelle (5 min)

| Métrique | Valeur | Seuil pour GO |
|----------|--------|---------------|
| 1. **Taux ouverture newsletters ?** | ___% | < 25% = Marge progression |
| 2. **Taux de clic ?** | ___% | < 2% = Opportunité |
| 3. **Temps création newsletter ?** | ___h | > 4h = ROI sur automatisation |

### Questions Segmentation (5 min)

4. **Segmentation actuelle : Manuelle ou auto ?**
   - Manuelle → Opportunité Einstein
   - Auto basique → Upgrade possible
   - Auto avancée → Peu de gains

5. **Combien de segments ?**
   - < 5 → Potentiel de granularité
   - > 10 → Déjà sophistiqué

### Test Impact (4 min)

6. **Si on fait 10 versions de newsletters, qui valide ?**
   - Process clair = GO
   - Complexe = Risque

7. **Budget actuel création contenu newsletter/an ?**
   - Pour calculer ROI automatisation

---

## 🎯 GRILLE DE DÉCISION POST-ENTRETIENS

### iPad Vendeur
| Critère | Validé ✓/✗ | Note |
|---------|------------|------|
| Vendeurs motivés (>7/10) | | |
| API existe | | |
| Gain >10min/vente | | |
| Budget <50k | | |
| **DÉCISION** | **GO / NO GO** | |

### CRM Prédictif
| Critère | Validé ✓/✗ | Note |
|---------|------------|------|
| Einstein dans licence | | |
| Action post-prédiction claire | | |
| Taux conversion <1% | | |
| Données suffisantes | | |
| **DÉCISION** | **GO / NO GO** | |

### Newsletter IA
| Critère | Validé ✓/✗ | Note |
|---------|------------|------|
| >4h création actuelle | | |
| API disponible | | |
| Process validation simple | | |
| Budget <30k | | |
| **DÉCISION** | **GO / NO GO** | |

---

## 📊 SYNTHÈSE FINALE

### Priorisation
1. **Piste prioritaire :** _________________ 
   - Pourquoi : _________________________

2. **Piste secondaire :** _________________
   - Pourquoi : _________________________

3. **Piste abandonnée :** _________________
   - Blocage principal : _________________

### Budget révisé
- Quick Win 1 : ________ CHF
- Quick Win 2 : ________ CHF
- **TOTAL** : ________ CHF

### Planning révisé
- Mois 1 : _____________________
- Mois 2 : _____________________
- Mois 3 : _____________________

### Risques identifiés
1. _______________________________
2. _______________________________
3. _______________________________

---

## ⏱️ SCRIPT DE CONCLUSION (2 min)

> "Merci pour ces insights. Basé sur vos retours, on recommande de commencer par [PISTE X] car [RAISON]. ROI attendu : [XXX CHF/mois] dès le mois [Y]. On peut faire un pilote sur [SCOPE] pour prouver la valeur. Next step ?"

---

## 📝 NOTES LIBRES

_Space pour capturer les insights non prévus :_

---

*Document de travail - Validation terrain pistes IA TAG Heuer*
*Groupe EMBA 3 - Septembre 2025*
