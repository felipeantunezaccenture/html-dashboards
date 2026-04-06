# Published Sites

Team HTML sites hosted on GitHub Pages.

**Live catalog:** https://felipeantunezaccenture.github.io/sites/

## How to publish a site

### If you are the repo owner

Run `/publish-html` in Claude Code with the HTML file.

### If you are a team member

1. Clone this repo: `git clone https://github.com/felipeantunezaccenture/sites.git`
2. Create a branch: `git checkout -b add/your-site-name`
3. Create a folder with your site name and add your HTML as `index.html`:
   ```
   mkdir your-site-name
   cp your-file.html your-site-name/index.html
   ```
4. Push and create a PR: `git push origin add/your-site-name`
5. Open a PR on GitHub — the repo owner will review and approve

Or run `/publish-html` in Claude Code and it will handle the PR for you.

## Structure

```
sites/
├── index.html              ← auto-generated catalog
├── site-a/
│   └── index.html
├── site-b/
│   └── index.html
└── ...
```
