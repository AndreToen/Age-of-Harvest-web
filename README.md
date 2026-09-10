# Age of Harvest — public web

Public site for the game (roadmap, links).  
Game code stays in the private **DFE Project** repo.

## Edit (easy)

Files live inside your DFE folder:

`DFE Project/Age-of-Harvest-web/`

- `index.html` — the page
- `assets/` — banner and images

Open `index.html` in a browser to preview.  
When happy, tell Cursor: **“sube la web”** (commit + push).

## First-time publish (you, once)

1. In Terminal (or ask Cursor): log in to GitHub CLI once:
   ```bash
   gh auth login
   ```
   Choose GitHub.com → HTTPS → Login with browser.

2. Then ask Cursor: **“crea el repo Age-of-Harvest-web y publícalo”**  
   Or run from this folder:
   ```bash
   gh repo create Age-of-Harvest-web --public --source=. --remote=origin --push
   ```

3. GitHub → repo **Age-of-Harvest-web** → **Settings** → **Pages**  
   - Source: Deploy from a branch  
   - Branch: `main` / folder: `/` (root) → Save  

4. Share: `https://andretoen.github.io/Age-of-Harvest-web/`  
   (username may match your GitHub account)

DFE Project stays **private**. Only this tiny site is public.
