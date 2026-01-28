## For Contributors (Fork Setup)

If you're contributing from a fork and want to preview your changes before opening a PR:

1. **Enable workflows on your fork**
   - Go to your fork's Actions tab
   - Click "I understand my workflows, go ahead and enable them" (green button)

2. **Enable Actions permissions**
   - Go to Settings → Actions → General
   - Select "Allow all actions and reusable workflows"
   - Enable "Read and write permissions"

3. **Make changes and push to your fork's main branch**
   - The deploy workflow will run automatically
   - This creates the `gh-pages` branch on your fork

4. **Enable GitHub Pages on your fork**
   - Go to Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select `gh-pages` branch and `/ (root)`
   - Click Save

5. **View your preview**
   - Your fork will be available at: `https://YOUR-USERNAME.github.io/TorranceSemple.github.io/`

6. **When satisfied, open a PR**
   - You'll also get a PR-specific preview at `/pr-preview/pr-{number}/`
