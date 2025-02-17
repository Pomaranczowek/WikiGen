# WikiGen

A bare bones static site generator made specifically for the Nekoweb wiki.

All content should be fully ported over now. However, more stuff may need to be
done.

## Contributing

* For contributing to the static site generator, please read [`CONTRIBUTING.md`](CONTRIBUTING.md).
* For contributing to the wiki, please see [the dedicated wikipage](https://wiki.nekoweb.org/contributing.html).

## Local Development

Before you can develop this locally, you'll need a few programs:

* Python
* PIP

### Get Dependencies

```bash
pip install -r requirements.txt
```

### Build

```bash
python main.py
```

### Dev Server

I do not currently know a good development server for Nekoweb sites,
bear with me.

## Directories

<!-- This table is a complete formatting nightmare lol -->

| Repo        | On Nekoweb | Purpose                                                                                   |
|-------------|------------|-------------------------------------------------------------------------------------------|
| `images`    | `/i`       | Static directory; contains embeded content on the wiki, such as images in the main content of pages.|
| `content`   | `/w`       | Parsed/MD directory; contains primary wiki pages, these are all included in `pages.html`. |
| `headpages` | `/`        | Parsed/MD directory; pages not under `/w` that still adhear to the formatting: `index`,`about`, `notfound`.|
| `static`    | `/`        | Static direcotry; static content that doesn't fall under `/i`: wiki background, `style.css`, `elements.css`, favicon, etc. |

## Licensing

See [COPYING](COPYING.md)
