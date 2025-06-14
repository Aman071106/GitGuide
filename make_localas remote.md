# 1. Navigate to your local project folder
cd path/to/ForestFireProject

# 2. Initialize Git (if not already done)
git init

# 3. Add the remote repository (replace <your-username>)
git remote add origin https://github.com/<your-username>/ForestFireProject.git

# 4. Fetch remote files (like README)
git fetch origin

# 5. Merge remote main into your local to avoid overwriting
git pull origin main --allow-unrelated-histories

# 6. Stage and commit your local files
git add .
git commit -m "Initial commit from local machine"

# 7. Push to GitHub
git push origin main
