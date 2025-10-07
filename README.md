# AgentCraft 2026 — Jekyll Site

This repository contains a ready-to-deploy Jekyll site using the **Minimalistic** theme by @vaibhavvikas.

## Quick start (GitHub Pages — no local setup)

1. Create a new GitHub repository (e.g., `agentcraft-2026`).
2. Upload all files from this folder to the repo root (or drag-and-drop the ZIP contents on GitHub).
3. Commit the changes.
4. In your repo, go to **Settings → Pages**.
   - Set **Source** to `Deploy from a branch`.
   - Select `main` (or `master`) branch and the `/ (root)` folder.
   - Save.
5. GitHub Pages will build your site. After a minute or two, your site will be live at  
   `https://YOUR-USERNAME.github.io/agentcraft-2026/`

> The site uses the theme as a **remote_theme**, which GitHub Pages supports out-of-the-box.

## Optional: Preview locally

If you want to run the site locally on your computer:

1. Install Ruby (3.1+ recommended). On macOS you can use `brew install ruby`.
2. Install Bundler: `gem install bundler`
3. From the project directory, run:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
4. Open `http://localhost:4000` in your browser.

---

### Where to edit content
- Edit `_config.yml` to change the title, description, sidebar navigation, or social links.
- Edit `index.md` to modify the Call for Papers text or add new sections.
- To add more pages, create additional `.md` files in the repo root with this header:
  ```yaml
  ---
  layout: default
  ---
  ```

**Theme docs**: See the theme’s README for advanced options like cards, logos, favicon, etc.