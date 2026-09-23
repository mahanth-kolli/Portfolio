# Mahanth Sai Kolli — Portfolio

```
portfolio/
├── index.html    ← all page content
├── style.css     ← colors, fonts, layout (variables at the top)
├── script.js     ← mobile menu, active link, scroll animations
└── assets/
    └── profile.png
```

## Run it locally
- **Easiest:** double-click `index.html` to open it in your browser.
- **VS Code:** install the "Live Server" extension, right-click `index.html`, then choose **Open with Live Server**. The page auto-reloads when you save.

## Edit your info
Search `index.html` for `EDIT:` comments. Your GitHub, LinkedIn and email links appear in the Projects button, the Contact section and the Footer. If you change one, update it in all three places.

- **Photo:** replace `assets/profile.png` with a square image and keep the same file name.
- **Skills:** copy or remove a `<article class="card skill-card">` block.
- **Journey:** change a milestone's class to `is-done`, `is-progress` or `is-planned`, and update the badge text.
- **Projects:** when you finish your first real project, delete the "Projects coming soon" block and uncomment the project card template just below it.
- **Colors:** change the variables in `:root` at the top of `style.css`.

## Deploy (free)
**GitHub Pages**
1. Create a repo (e.g. `portfolio`) and upload all the files, keeping the folder structure.
2. In the repo, open **Settings → Pages**, set Source to *Deploy from a branch*, choose `main` / `root`, then click **Save**.
3. After a minute your site is live at `https://<username>.github.io/portfolio/`.

**Netlify:** go to app.netlify.com/drop and drag the `portfolio` folder onto the page.
**Vercel:** import the GitHub repo and use the default settings (no build step).

## Final checklist
- [ ] Every nav link scrolls to the right section
- [ ] GitHub, LinkedIn and Email links open correctly
- [ ] Mobile (~375px): menu opens and closes, and there's no sideways scrolling
- [ ] Tablet (~768px) and desktop (1280px+) layouts look right
- [ ] Tab through the page with the keyboard: every link and button shows a focus outline
- [ ] The profile photo loads after deploying (file names are case-sensitive on servers)
