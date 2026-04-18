### My DWM

How to create a new git repo on the cli in archlinux, 
I have git and github-cli installed, and I am not logged in to github

mkdir my-project  
cd my-project  
git init  

echo "# My Project" > README.md  
git add .  
git commit -m "Initial commit"  

gh auth login  
gh auth status  

gh repo create my-project --public --source=. --remote=origin  

git push -u origin main  

```bash
mkdir my-project  
cd my-project  
git init  
```

