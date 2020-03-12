How to find all therapists/psychologists covered by UHC and with certain modalities in your area (using psychology today data):

1. Use UHC site to filter pratictioners and click "Print"
2. Right click on page in Chrome and click "Save Page As..." then select "Complete Webpage"
3. Move the HTML file to this directory and rename as `site.html`
4. `conda create -c conda-forge -n search-therapy jupyterlab beautifulsoup4 requests tqdm requests-cache && conda activate && jupyter lab Untitled.ipynb`
5. Run the notebook.
6. Many URLs will open in your browser. Good luck!


Why not just use psychology today's provider filtering? I have found it's not that accurate. Many providers advertise as UHC but then actually are out of network.

Why write a script? Because there are 100s of providers in NYC and I grew tired of copy and pasting names.