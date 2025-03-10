# 1. Build for Surge with the Surge base URL
hugo --baseURL mr.knapp.surge.sh

# 2. Deploy to Surge
surge ./public https://mr.knapp.surge.sh

# 3. Build for GitHub Pages with the GitHub Pages base URL
hugo --baseURL https://timothymknapp.github.io/MCV4U_site/

# 4. Deploy to GitHub Pages
# Checkout the gh-pages branch
git checkout gh-pages

# Copy the contents of the public directory to the root of the repository
cp -r public/* .

# Add, commit, and push the changes to GitHub Pages
git add .
git commit -m "Update site with new content"
git push origin gh-pages --force

# 5. Switch back to the master (or main) branch for further development
git checkout master
