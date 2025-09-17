# Techniques de prompting avancé en matière juridique

Cette page présente des exemples concrets de techniques de prompting spécialement conçues pour les professionnels du droit, avec des cas d'usage pratiques et des modèles prêts à l'emploi.

## 1. Analyse contractuelle structurée

### Technique : Prompt par étapes avec rôle spécialisé

```
Tu es un juriste expert en droit des contrats. Analyse le contrat ci-joint selon cette méthodologie :

ÉTAPE 1 - Identification
- Type de contrat
- Parties contractantes
- Objet principal

ÉTAPE 2 - Clauses critiques
- Obligations principales de chaque partie
- Conditions suspensives ou résolutoires
- Clauses de responsabilité et de limitation

ÉTAPE 3 - Risques juridiques
- Points d'attention prioritaires
- Clauses déséquilibrées
- Manquements aux obligations légales

ÉTAPE 4 - Recommandations
- Modifications suggérées
- Négociations à prévoir

Format de sortie : Tableau synthétique + points d'alerte
```

## 2. Recherche jurisprudentielle ciblée

### Technique : Contexte enrichi avec critères de pertinence

```
Contexte : Je travaille sur un dossier de responsabilité médicale concernant [décrire le cas].

Tâche : Identifie 5 arrêts de la Cour de cassation des 10 dernières années pertinents pour ce cas.

Critères de sélection :
1. Similarité factuelle avec le cas présent
2. Principe juridique applicable
3. Évolution récente de la jurisprudence

Pour chaque arrêt, fournis :
- Référence complète (Cour, date, numéro)
- Résumé des faits en 2 lignes
- Principe juridique dégagé
- Applicabilité au cas présent (score sur 10)

Sources à privilégier : Légifrance, Dalloz, base JADE
```

## 3. Rédaction de conclusions juridiques

### Technique : Structure argumentaire avec syllogisme juridique

```
Rédige des conclusions en suivant cette structure :

RÔLE : Tu es avocat devant le Tribunal de [juridiction]

CONTEXTE : [Résumé des faits et prétentions]

STRUCTURE IMPOSÉE :
I. EN DROIT
   - Rappel des textes applicables
   - Analyse jurisprudentielle
   - Doctrine pertinente

II. EN L'ESPÈCE
   - Application des règles aux faits
   - Syllogisme juridique pour chaque moyen

III. DEMANDES
   - Prétentions principales
   - Subsidiairement
   - Dépens

STYLE : Juridique soutenu, phrases courtes, connecteurs logiques
LONGUEUR : Maximum 3 pages
ÉVITER : Répétitions, arguments émotionnels, références non vérifiées
```

## 4. Due diligence automatisée

### Technique : Check-list exhaustive avec scoring

```
Tu es un juriste en M&A. Effectue une due diligence préliminaire de cette société.

DOCUMENTS À ANALYSER : [Liste des documents fournis]

GRILLE D'ANALYSE :
□ Statuts et K-bis (conformité, capital, dirigeants)
□ Assemblées générales (régularité, résolutions)
□ Contrats significatifs (> 100k€, durée > 2 ans)
□ Propriété intellectuelle (marques, brevets, licences)
□ Contentieux (procédures en cours, provisions)
□ Social (conventions collectives, litiges prud'homaux)
□ Environnement (autorisations, études d'impact)

NOTATION :
- Vert : Conforme, risque faible
- Orange : Points d'attention, vérifications nécessaires
- Rouge : Risque majeur, investigation approfondie requise

LIVRABLE : Rapport synthétique + matrice des risques + plan d'action
```

## 5. Veille réglementaire personnalisée

### Technique : Filtrage intelligent avec alertes

```
Tu es un juriste spécialisé en [domaine]. Analyse cette actualité juridique et détermine sa pertinence pour mes dossiers.

TEXTE À ANALYSER : [Article/décret/jurisprudence]

CRITÈRES DE PERTINENCE :
1. Impact sur mes secteurs d'activité : [liste des secteurs]
2. Effet sur mes clients type : [profils clients]
3. Délai d'application et mesures transitoires
4. Niveau d'urgence de l'information

ANALYSE ATTENDUE :
- Résumé exécutif (3 lignes max)
- Changements concrets par rapport à l'état du droit antérieur
- Actions à entreprendre (délais, formalités)
- Clients à alerter en priorité
- Score d'urgence (1-5)

Si score ≥ 3 : Rédige un projet de note d'information client
```

## 6. Négociation contractuelle assistée

### Technique : Simulation et contre-propositions

```
CONTEXTE : Négociation d'un contrat de [type] avec [profil de cocontractant]

MA POSITION : [Objectifs prioritaires et lignes rouges]
LEUR POSITION : [Demandes adverses connues]

MISSION :
1. Analyse des positions en présence
2. Identification des zones de compromis possibles
3. Stratégie de négociation par phases
4. Rédaction de contre-propositions argumentées

CONTRAINTES :
- Respecter l'équilibre contractuel
- Anticiper les objections juridiques
- Proposer des alternatives créatives
- Préserver la relation commerciale

LIVRABLES :
- Tableau comparatif des positions
- Script de négociation par point
- Versions alternatives des clauses sensibles
- Arguments juridiques pour chaque position
```

## 7. Formation juridique interactive

### Technique : Cas pratique génératif

```
Tu es formateur en droit [matière]. Crée un cas pratique pédagogique.

OBJECTIF PÉDAGOGIQUE : Maîtrise de [notion juridique précise]

PARAMÈTRES :
- Niveau : [débutant/intermédiaire/expert]
- Durée de résolution : [temps estimé]
- Difficultés à intégrer : [liste des pièges classiques]

STRUCTURE DU CAS :
1. Énoncé factuel réaliste (sans indices trop évidents)
2. Documents annexes pertinents
3. Questions progressives (facile → complexe)
4. Corrigé détaillé avec alternative
5. Points de droit essentiels à retenir
6. Variantes possibles pour approfondir

CRITÈRES QUALITÉ :
- Vraisemblance des faits
- Actualité juridique
- Progression pédagogique
- Richesse des apprentissages
```

---

## Bonnes pratiques du prompting juridique

### Précision terminologique
- Utilisez le vocabulaire juridique exact
- Précisez la juridiction et le système juridique
- Indiquez les sources de droit pertinentes

### Structuration des demandes
- Décomposez les questions complexes
- Numérotez les étapes d'analyse
- Définissez clairement les livrables attendus

### Contextualisation
- Fournissez le cadre factuel complet
- Précisez les enjeux et contraintes
- Indiquez le public cible de l'analyse

### Vérification et validation
- Demandez toujours les sources
- Croisez avec vos connaissances
- Validez les références jurisprudentielles

---

*Ces techniques sont des points de départ à adapter selon vos besoins spécifiques. L'efficacité du prompting s'améliore avec la pratique et l'itération.*