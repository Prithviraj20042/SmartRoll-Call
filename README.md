# 1. Navigate to your folder (replace with your actual folder path)
cd path/to/your/SmartRoll-Call

# 2. Set up the local repository
git init
git add .
git commit -m "Initial commit of project files"

# 3. Connect it to GitHub and sync your new README
git branch -M main
git remote add origin https://github.com/Prithviraj20042/SmartRoll-Call.git
git pull origin main --allow-unrelated-histories

# 4. Push it online!
git push -u origin main
