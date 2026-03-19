# MareSphere — static website

Plain **HTML + CSS** only (no build, no JavaScript). Each screen is its **own `.html` file**, linked with **relative** URLs.

## Entry

- **`index.html`** (root) → redirects to **`de/`** (`de/index.html`)

## Pages (mirror under `de/` and `en/`)

| File | Role |
|------|------|
| `index.html` | Home |
| `about.html` | About |
| `services.html` | All services |
| `service-nautisch-technische-koordination.html` | Service detail |
| `service-maritime-notfallkoordination.html` | Service detail |
| `service-ersatzteilbeschaffung.html` | Service detail |
| `service-maritime-services.html` | Service detail |
| `service-dokumentations-zertifikatsmanagement.html` | Service detail |
| `service-bereederungsmanagement.html` | Service detail |
| `contact.html` | Contact + form |
| `agb.html` | Legal placeholder |
| `sitemap.html` | List of all pages (both languages) |

## Also in the repo

- **`css/styles.css`** — styles  
- **`assets/`** — images  
- **`favicon.svg`**, **`robots.txt`**

## Navigation

- Header and footer on every page link to the main sections.  
- Footer **Dienstleistungen / Services** lists all six service detail pages.  
- Service detail pages include **← Back to services**.  
- **Übersicht / Site map** in the nav and **`sitemap.html`** link every HTML file.

## Preview

```bash
python3 -m http.server 8080
```

Open `http://localhost:8080/` → you land on the German home page.
