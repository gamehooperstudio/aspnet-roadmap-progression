💻 Exercice pratique (100 % réel)
1. 🌱 Initialise un projet :
mkdir ProjetGitTest
cd ProjetGitTest
dotnet new console
git init


2. 💬 Fais des commits :
Ajoute du code, puis :
git add .
git commit -m "Initial commit avec Hello World"


3. 🌐 Crée un repo sur github.com
Nomme-le aspnet-roadmap-progression
Lie-le à ton projet :
git remote add origin https://github.com/ton-pseudo/aspnet-roadmap-progression.git
git branch -M main
git push -u origin main


5. 🌿 Crée une branche :
git checkout -b jour-3-exo
Fais un petit changement dans le code
Commit & push

🧩 Bonus : Test de merge
Reviens sur main, fais un changement
Merge avec la branche :
git merge jour-3-exo
