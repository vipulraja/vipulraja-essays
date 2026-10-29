# vipulraja-essays

Personal essay site: Hugo + PaperMod, deployed free on GitHub Pages, served on a custom domain.

## Write a new essay

```bash
hugo new content essays/my-essay-slug/index.md   # creates a draft from archetypes/essays.md
hugo server -D                                   # live preview at http://localhost:1313 (drafts included)
```

Set `draft: false`, then commit and push to `main`. GitHub Actions builds and deploys the site in about a minute.

## Pre-publish checklist

- [ ] No confidential, need-to-know, customer-identifying, or personal user data
- [ ] Consider go/publish (PubApprove) if the essay draws on Google work or a competitive topic
- [ ] The site-wide footer disclaimer covers the "opinions are my own" requirement

## Layout

| Path | Purpose |
|---|---|
| `hugo.yaml` | Site config: title, menus, social links, analytics token |
| `content/essays/<slug>/index.md` | One folder per essay; images go in the same folder |
| `content/about.md` | About page |
| `layouts/partials/extend_footer.html` | Disclaimer footer |
| `layouts/partials/extend_head.html` | Optional Cloudflare Web Analytics |
| `static/CNAME` | Custom domain for GitHub Pages |
| `.github/workflows/deploy.yml` | Build and deploy on push |
