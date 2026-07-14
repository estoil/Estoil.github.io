# Xingyun Wang's Homepage

Personal academic homepage for **Xingyun Wang (王星运)**, an undergraduate in Computer Science at Peking University.

Live site: [https://estoil.github.io](https://estoil.github.io)

Research interests: Embodied AI, Whole-Body Tracking, Locomotion, LLM Safety.

## Customize

| File / Asset | What to edit |
| --- | --- |
| `contents/config.yml` | Site title, nav name, section list, backgrounds, copyright, GitHub / license links |
| `contents/home.md` | Bio, contact, education, research interests |
| `contents/publications.md` | Papers (Markdown) |
| `contents/awards.md` | Awards (Markdown) |
| `static/assets/img/photo.jpg` | Profile photo (used in `index.html`) |
| `static/assets/favicon.ico` | Browser tab icon |
| `static/assets/background/` | Hero background images listed in `config.yml` |

After editing Markdown or config, refresh the page (hard refresh if needed). No build step is required.

## Local preview

Serve the repo root over HTTP (opening `index.html` as a file URL may block Markdown fetches):

```bash
# Python
python -m http.server 8000

# or Node
npx serve .
```

Then open `http://localhost:8000`.

## Deploy (GitHub Pages)

This repo is intended as `estoil.github.io`. Push to the `main` branch and enable GitHub Pages from the repository root.

## Credits

Based on the open-source academic webpage template by [senli1073](https://github.com/senli1073). See [LICENSE](LICENSE) for details.
