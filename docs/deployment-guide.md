# Deployment Process for Surge and GitHub Pages

## 1. Commit Content Updates to Master Branch

### Overview
After making content updates locally, the first step is to commit your changes to the `master` branch to ensure your repository is up to date before deploying to either Surge or GitHub Pages.

### Steps in VS Code

1. **Open VS Code** in your project directory (`NIPOGI_calculus_site`).
2. **Stage Changes**:
   - In VS Code, go to the **Source Control** panel on the left sidebar (it looks like a branching tree).
   - You’ll see all your modified files under **Changes**.
   - Click on the **+** icon next to each file you want to stage or **+** next to **Changes** to stage all files.
3. **Commit Changes**:
   - Once your files are staged, type a commit message in the text box (e.g., "Content updates for the day").
   - Click the **checkmark** icon at the top to commit your changes.
4. **Push Changes to GitHub**:
   - Open the **Terminal** within VS Code (Ctrl+` or via the menu: Terminal > New Terminal).
   - Run the following command to push your changes to the `master` branch:
     ```bash
     git push origin master
     ```
   - If prompted, enter your GitHub credentials.

> **Note**: If you haven’t already set up your GitHub credentials in VS Code, you may be prompted to enter them when pushing changes. You can also use GitHub’s authentication token as the password if needed.

Once you’ve committed and pushed your changes to `master`, your project is ready to be deployed to both Surge and GitHub Pages.

---

## 2. Deploy to Surge

### Steps:

1. **Build for Surge**:
   - Run the following Hugo command to build your site for Surge:
     ```bash
     hugo --baseURL https://mr.knapp.surge.sh
     ```
   - This will build your site and prepare the `public` folder for deployment.

2. **Deploy to Surge**:
   - Run the following command to deploy to Surge:
     ```bash
     surge ./public --domain mr.knapp.surge.sh
     ```

---

## 3. Deploy to GitHub Pages

### Steps:

1. **Build for GitHub Pages**:
   - Run the following Hugo command to build for GitHub Pages:
     ```bash
     hugo --baseURL https://timothymknapp.github.io/MCV4U_site/
     ```
   - This will generate the necessary files in the `public` folder for GitHub Pages.

2. **Check out the `gh-pages` branch**:
   - Run the following command to check out the `gh-pages` branch:
     ```bash
     git checkout gh-pages
     ```

3. **Deploy to GitHub Pages**:
   - Push the `public` folder to the `gh-pages` branch using:
     ```bash
     git push origin gh-pages --force
     ```

4. **Switch back to the `master` branch**:
   - Once the deployment is complete, return to the `master` branch to continue content development:
     ```bash
     git checkout master
     ```

---

## Conclusion

By following these steps, you’ll ensure that your updates are deployed on both Surge and GitHub Pages. This process allows you to deploy to both platforms without interrupting your local development workflow. Let me know if you encounter any issues or need further adjustments!
