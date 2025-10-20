# github-flow

🧭 1. What is GitHub Flow?

GitHub Flow is a simple, lightweight workflow for managing collaboration and version control in software projects using Git and GitHub.
It defines how developers should work with branches, commits, pull requests, and deployments in a clear and efficient cycle.

Created by: GitHub team (especially Scott Chacon and Ben Balter)

Introduced in: 2011, on the GitHub Blog

It was designed as a simpler alternative to Git Flow for projects that deploy frequently.





⚙️ 2. How Does GitHub Flow Work?

GitHub Flow is based on branching — every new feature or fix is developed in a separate branch and merged into the main branch through a pull request.

🔄 The Basic Cycle:

Create a branch

git checkout -b feature-login


Make changes & commit

git add .
git commit -m "Add login form"


Push the branch to GitHub

git push origin feature-login


Open a Pull Request (PR)
→ To propose your changes and discuss them with your team.

Review & Approve
→ Team members review the code, comment, and suggest improvements.

Merge the Pull Request
→ Once approved, it’s merged into the main branch.

Deploy
→ The main branch should always be ready for deployment.




🎯 3. Why Do We Use GitHub Flow?


💡 Advantage	                                   Explanation
✅ Simplicity	                                   Easier to understand and use than Git Flow.
🔄 Continuous Integration	                       Encourages frequent updates and testing.
👥 Collaboration	                               Pull requests make teamwork and feedback easy.
🚀 Fast Deployment	                             Perfect for web projects that deploy many times a day.
🔐 Code Quality	Reviews                          before merging ensure better code quality.




🤝 4. Bonnes Pratiques de Collaboration

✅ Nommer clairement les branches

Exemple : feature/add-login, bugfix/fix-header

✅ Faire des commits clairs et fréquents

Exemple : git commit -m "Fix navbar responsiveness"

✅ Travailler sur des branches courtes

Pour éviter les conflits et garder le code à jour.

✅ Relire le code (Code Review)

Toujours passer par une Pull Request avant de merger.

✅ Maintenir la branche main stable

main doit toujours être prête à être déployée.

✅ Communiquer dans les PR

Discuter, commenter, expliquer les choix techniques.
