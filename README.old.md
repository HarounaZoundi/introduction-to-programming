# introduction-to-programming
Introduction to Programming
# Adding the GitHub Pages dependency package
npm install gh-pages --save-dev
# Adding the properties to the package.json file
"homepage": "https://<Username>.github.io/<Repository-name>"
# Add “deploy” and “predeploy “properties in the script field
"scripts":{
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build" 
} 

git add .
git commit -m "commit"
git push
npm run deploy

# GitHub CLI
brew install gh
gh auth login



