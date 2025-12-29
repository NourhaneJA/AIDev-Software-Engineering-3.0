# AIDev-Software-Engineering-3.0
Étude empirique de la collaboration entre agents IA et développeurs humains sur GitHub à partir du dataset AIDev (SE 3.0, Mining Software Repositories).

## Description

Ce projet s’inscrit dans le cadre du **MSR 2026 Mining Challenge** et vise à analyser comment les agents de programmation basés sur l’**intelligence artificielle** collaborent avec les développeurs humains dans des projets GitHub réels.  
Le projet exploite le **dataset AIDev**, qui contient des pull requests générées par des agents IA comme OpenAI Codex, GitHub Copilot, Devin, Cursor, et Claude Code.  

L’objectif principal est de comprendre :  
- L’efficacité et la qualité des contributions IA  
- Les interactions et feedback des développeurs humains  
- La capacité des agents IA à apprendre et améliorer leurs contributions  


## Objectif de l’étude (Goal)

Évaluer dans quelle mesure les agents de programmation IA s’intègrent efficacement dans les workflows collaboratifs GitHub, en analysant leurs contributions, les interactions humaines et l’impact sur le processus de revue de code.

## Questions de recherche (Research Questions)

- **RQ1** : Dans quelle mesure les contributions des agents IA sont-elles acceptées comme du code de qualité dans les projets open source ?  
- **RQ2** : Quels types d’interactions et de feedback les développeurs humains fournissent-ils aux pull requests générées par des agents IA ?  
- **RQ3** : Les agents IA sont-ils capables d’apprendre du feedback humain et d’améliorer leurs contributions au cours du processus de revue ?

##  Métriques associées (Metrics)

- **RQ1** : Taux de PR fusionnées, temps moyen avant fusion/rejet, nombre moyen de commits par PR  
- **RQ2** : Nombre de commentaires de revue, nature du feedback (style, correction, tests, sécurité), décision de revue (approbation, modifications)  
- **RQ3** : Proportion de commentaires traités par l’IA, nombre de commits correctifs après revue, délai de réponse de l’IA aux commentaires humains  

## Structure du dataset AIDev

- **Niveau Pull Request** : titre, description, agent auteur, dates clés, état de la PR  
- **Niveau Repository** : langage principal, licence, popularité (étoiles, forks)  
- **Niveau Développeur** : ancienneté, activité, participation aux revues de code  

## Méthodologie

L’étude utilise l’approche **Goal–Question–Metric (GQM)** pour structurer la recherche et analyser les interactions humain–IA.  
Le sous-ensemble du dataset utilisé comprend uniquement les dépôts populaires avec plus de 100 étoiles GitHub pour garantir la qualité des données et l’activité collaborative.

## Contributions attendues

- Compréhension du rôle réel des agents IA dans le développement collaboratif  
- Identification des limites des agents IA face aux exigences humaines  
- Recommandations pour améliorer la collaboration humain–IA  
- Apport empirique aux recherches MSR sur l’ingénierie logicielle assistée par IA  

## Références

- « The Rise of AI Teammates in Software Engineering (SE 3.0) : How Autonomous Coding Agents Are Reshaping Software Engineering »  
- Dataset AIDev (MSR 2026 Mining Challenge)  


## Tags / Topics

`AI, Artificial-Intelligence, Software-Engineering, SE3.0, GitHub, Mining-Software-Repositories, MSR2026, Pull-Requests, Empirical-Study, Code-Review, AIDev, Human-AI-Collaboration
