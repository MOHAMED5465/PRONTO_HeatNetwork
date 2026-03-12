# PRONTO – Réseau de Chaleur

**Chaud pour décider ?**

Projet d’optimisation de réseau de chaleur développé dans le cadre du module PRONTO à IMT Atlantique, semestre 6 (année 2024-2025).

## Équipe
  
- Mohamed RHARRASSI
- Mohamed Amine JANATI
- Mélina WANG
- Rayan BOUAKAR  
- **Encadré par** : Patrick Meyer & Célia Benmansour

## Objectif

Concevoir des algorithmes d’aide à la décision pour **dimensionner un réseau de chaleur** de manière optimale, en respectant :
- des **contraintes physiques** (capacité, pertes thermiques, structure arborescente),
- des **enjeux économiques** (coût d’investissement, revenu, pénalités),
- et différents **scénarios d’usage** (équité, résilience, efficacité énergétique).

## Fonctionnalités

Le projet inclut :
- **Modélisation mathématique** complète du réseau et des contraintes ;
- **Résolution exacte via le solveur CBC** ;
- **Résolution approchée via ILS** ;
- **Prise en compte de scénarios complexes** :  
  - *Scénario 1* : Équité entre usagers ;  
  - *Scénario 2* : Résilience face aux pannes ;  
  - (*Scénario 3* : Minimisation des pertes thermiques – non implémenté mais abordé).

## Structure du dépôt

```bash
📁 PRONTO-HeatNetwork
│
├── 📁 BigData/                     # Données et scripts pour les jeux de données volumineux
├── 📁 SmallData/                  # Données et scripts pour les jeux de données réduits
├── 📁 Scénario 1/                 # Implémentation du scénario Équité
├── 📁 Scénario 2/                 # Implémentation du scénario Résilience
├── 📁 Distribution Prioritaire/  # Tentative de scénario sur la priorisation
│
├── 📄 LICENSE                     # Licence du projet (MIT, GPL, etc.)
├── 📄 README.md                   # Présentation du projet (ce fichier)
├── 📄 PRONTO_rapport_final.pdf          # Rapport final détaillé
├── 📄 PRONTO_présentation_détaillée.pdf  # Support de présentation
