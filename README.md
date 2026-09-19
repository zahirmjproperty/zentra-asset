# Zentra Asset

Property, tenancy and asset management system — Zentra Property Group.

- **Host:** https://asset.zentrapropertygroup.com
- **Status:** Phase 1 (environment). Deployment is phased; no application modules are live yet.
- **Visibility:** internal system, `noindex` until approved for public discovery.

## Structure

| Path | Purpose |
|---|---|
| `index.html` | Landing page for this environment |
| `CNAME` | Custom domain binding for GitHub Pages |
| `robots.txt` | Disallow all crawlers (internal system) |
| `.gitignore` | Blocks snapshot/data artifacts from being committed |
| `portal/` | (Phase 2+) application modules — added only after tenant separation |

## Related systems

| System | Host |
|---|---|
| Mr Tanah — public property listings | `mrtanah.com` |
| Zahir MJ Property | `zahirmjproperty.com` |

Zentra Asset is a **separate** system. Mr Tanah/ZMP remain listings-only.

## Deployment

Static site served by GitHub Pages from `main`. Never commit data snapshots, tenant records or credentials into this repository.
