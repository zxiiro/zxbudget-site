# ZxBudget site

Public pages for [zxbudget.zxiiro.ca](https://zxbudget.zxiiro.ca/).
Issues are tracked in [zxiiro/zxbudget](https://github.com/zxiiro/zxbudget/issues/376),
not in this repo.

## URLs that stay put

| Path | Page |
| --- | --- |
| `/` | Landing page. App Store marketing URL. |
| `/support.html` | Support. App Store support URL, once that field is updated. |
| `/privacy.html` | Privacy policy. App Store privacy policy URL. Do not move this path. |
| `/guides/` | Guide index. Links only pages that exist. |
| `/guides/quick-start/` | Quick start. |

## Develop

Node 22 (`/.nvmrc`).

```bash
npm install
npm run dev    # http://localhost:8080
npm run build  # writes _site/
```

Edit files in `src/`. `_site/` is generated. GitHub Actions builds and
publishes on every push to `main`.

The privacy policy wording is the legal text already on the App Store
listing. Change it only with an explicit decision and a new "Last updated"
date.
