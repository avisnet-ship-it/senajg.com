# Sena JG — author website (senajg.com)

The English-language website of the author Sena JG, published at <https://senajg.com/>. The Portuguese-language website is at <https://senajg.com.br/>.

## Version

Current version: **v4.1.0** (SenaJG-rev.66), 2026-11-14. The first version of this website was v4.0.0 (SenaJG-rev.58), 2026-10-30: the international domain, senajg.com, for the website in English. Each version has a Release page in this repository, with a summary of what changed: <https://github.com/avisnet-ship-it/senajg.com/releases>. The version process (tags, branches and Releases) is in `VERSIONING.md`, in the project's private repository, `avisnet-ship-it/privado`; the `CLAUDE.md` here reminds Claude to read it before acting.

## Where each page is

| Address | What it is |
|---|---|
| `/` | the author's page: humanist books |
| `/everyday/` | books on finance and everyday life |
| `/<folder>/` — the 6 books (list below) | **folders of this repository** |
| `/come-funziona-la-realta/` | How does The Reality work? in Italian (since rev.67): the same page, in Italian, leading to the English edition on amazon.it |

## The 6 books (folder = address)

1. The Cosmic Christ — `the-cosmic-christ/`
2. The Barn Of This Life — `the-barn-of-this-life/`
3. The Solution to Everything in Life — `the-solution-to-everything-in-life/`
4. How does The Reality work? — `how-does-the-reality-work/`
5. Money Vol. 1 — `money-vol-1/`
6. Succeed On Kindle — `succeed-on-kindle/`

## Files
- `CNAME` — custom domain (`senajg.com`)
- `.nojekyll` — publishes the files exactly as they are
- `.gitattributes` — Git rules for the files (line endings, and images as binary)
- `robots.txt` — the only one that search engines read on the domain; it points to the sitemap
- `sitemap.xml` — a single map with all the pages of the website
- `404.html` — error page with a button to the home page
- `favicon.ico` — browser tab icon (blue mandala, 16, 32 and 48 px)
- `apple-touch-icon.png` — 180×180 icon for people who save the website to the home screen of an iPhone or iPad
- `assets/` — the covers on the cards and the icons of the main pages; `aco-escovado.js` (the spinning metal buttons), `seta-voltar.js` (the spinning arrow of the Back button), the photos of the city mirror on the Kindle buttons (`mirror-city.webp` and `mirror-eagle.webp`), and the background of the Reality pages: `fundo-bolhas.js` (the rotating bubble-universe images, `universo-bolha-1.webp` to `universo-bolha-4.webp`) and `cubos-metal.webp` (the metal cubes)
- `AGENTS.md` and `CLAUDE.md` — instructions for AI agents, pointing to the private repository
