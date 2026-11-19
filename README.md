# SLADE project page

Project website for **SLADE: Shielding against Dual Exploits in Large Vision-Language Models** (CVPR 2025), by Md Zarif Hossain and Ahmed Imteaj.

It is a single static page (`index.html`) with its assets in `src/`, so it can be served directly by GitHub Pages.

- `src/fig1.png`, `src/fig2.png`, `src/fig3.png`: figures cropped from the paper
- `src/*_clean.png`, `src/*_adv.png`: example images used in the interactive demo
- `src/SLADE_CVPR2025.pdf`: the paper

To preview locally:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

Code: https://github.com/speedlab-git/SLADE

The CVF Open Access button is a placeholder (`href="#"`); update it in `index.html` once the URL is set.
