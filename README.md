# WikiGen

I bare bones static site generator made specifically for the Nekoweb wiki.

All content should be fully ported over now. However, more stuff may need to be
done.

## Local Development

Before you can develop this locally, you'll need a few programs:

* Python
* PIP

### Get Dependencies

```bash
pip -r requirements.txt
```

### Build

```bash
python main.py
```

### Dev Server

I do not currently know a good development server for Nekoweb sites,
bear with me.

## Directories

| Repo        | On Nekoweb | Purpose |
|-------------|------------|---------|
| `images`    | `/i`       | Static directory; contains embeded content on the wiki, such as images in the main content of pages. |
| `content`   | `/w`       | Parsed/MD directory; contains primary wiki pages, these are all included in `pages.html`. |
| `headpages` | `/`        | Parsed/MD directory; pages not under `/w` that still adhear to the formatting: `index`, `about`, `notfound`.|
| `static`    | `/`        | Static direcotry; static content that doesn't fall under `/i`: wiki background, `style.css`, `elements.css`, favicon, etc. |

