# github-flow

🧭 1. Qu’est-ce que GitHub Flow ?

GitHub Flow est un flux de travail simple et léger qui permet de gérer la collaboration et le contrôle de version dans les projets logiciels utilisant Git et GitHub.
Il définit comment les développeurs doivent travailler avec les branches, les commits, les pull requests et les déploiements dans un cycle clair et efficace.

Créé par : L’équipe GitHub (notamment Scott Chacon et Ben Balter)

Introduit en : 2011, sur le blog officiel de GitHub

Il a été conçu comme une alternative plus simple à Git Flow, adaptée aux projets déployés fréquemment.

⚙️ 2. Comment fonctionne GitHub Flow ?

GitHub Flow est basé sur les branches — chaque nouvelle fonctionnalité ou correction est développée dans une branche séparée, puis fusionnée dans la branche principale (main) via une Pull Request.

🔄 Le cycle de base :

Créer une branche
→ À partir de main

git checkout -b feature-login


Faire des modifications et valider (commit)

git add .
git commit -m "Ajout du formulaire de connexion"


Pousser la branche sur GitHub

git push origin feature-login


Ouvrir une Pull Request (PR)
→ Pour proposer vos changements et en discuter avec l’équipe.

Relecture et approbation du code
→ Les membres de l’équipe examinent le code, laissent des commentaires et suggèrent des améliorations.

Fusionner la Pull Request
→ Une fois approuvée, la branche est fusionnée dans main.

Déployer
→ La branche main doit toujours être prête à être déployée.

🎯 3. Pourquoi utilisons-nous GitHub Flow ?
💡 Avantage	🧩 Explication
✅ Simplicité	         Plus facile à comprendre et à utiliser que Git Flow.
🔄 Intégration        continue	Encourage des mises à jour et des tests fréquents.
👥 Collaboration	     Les Pull Requests facilitent le travail d’équipe et le feedback.
🚀 Déploiement         rapide	Idéal pour les projets web déployés plusieurs fois par jour.
🔐 Qualité du code	   Les revues avant la fusion garantissent un code plus propre et stable.

🤝 4. Bonnes pratiques de collaboration

✅ Nommer clairement les branches

Exemple : feature/add-login, bugfix/fix-header

✅ Faire des commits clairs et fréquents

Exemple : git commit -m "Correction du responsive de la barre de navigation"

✅ Travailler sur des branches courtes

Pour éviter les conflits et garder le code à jour.

✅ Relire le code (Code Review)

Toujours passer par une Pull Request avant de fusionner.

✅ Maintenir la branche main stable

main doit toujours être prête à être déployée.

✅ Communiquer dans les Pull Requests

Discuter, commenter, expliquer les choix techniques pour une meilleure collaboration.










1️⃣ Question :
Qui a créé GitHub Flow ?
A) Google
B) Microsoft
C) L’équipe GitHub (Scott Chacon & Ben Balter) ✅
D) Linus Torvalds

2️⃣ Question :
En quelle année GitHub Flow a-t-il été introduit ?
A) 2008
B) 2011 ✅
C) 2015
D) 2018

3️⃣ Question :
À quoi sert principalement GitHub Flow ?
A) Gérer des bases de données
B) Concevoir des interfaces utilisateur
C) Gérer la collaboration et le contrôle de version ✅
D) Tester des applications mobiles

4️⃣ Question :
GitHub Flow a été créé comme une alternative plus simple à quel workflow ?
A) Waterfall
B) Git Flow ✅
C) Agile
D) Scrum

5️⃣ Question :
Dans GitHub Flow, chaque nouvelle fonctionnalité ou correction est développée dans...
A) La branche principale (main)
B) Une nouvelle branche ✅
C) Le serveur
D) La base de données

6️⃣ Question :
Quel est le but d’une Pull Request (PR) ?
A) Supprimer du code
B) Proposer et discuter des changements ✅
C) Renommer des branches
D) Installer des dépendances

7️⃣ Question :
Laquelle de ces étapes ne fait pas partie du cycle GitHub Flow ?
A) Créer une branche
B) Faire des commits
C) Fusionner la Pull Request
D) Redémarrer son ordinateur ✅

8️⃣ Question :
Pourquoi utilisons-nous GitHub Flow ?
A) Parce qu’il est lent mais sécurisé
B) Parce qu’il est simple, collaboratif et permet des déploiements rapides ✅
C) Parce qu’il corrige automatiquement tous les bugs
D) Parce qu’il remplace Git

9️⃣ Question :
Laquelle de ces propositions est une bonne pratique de collaboration ?
A) Travailler directement sur main
B) Sauter la relecture de code
C) Utiliser des noms de branches clairs ✅
D) Éviter les commits

🔟 Question :
Que doit toujours représenter la branche main dans GitHub Flow ?
A) Elle peut contenir du code non terminé
B) Elle doit toujours être prête à être déployée ✅
C) Elle doit être supprimée régulièrement
D) Elle ne doit jamais être mise à jour
