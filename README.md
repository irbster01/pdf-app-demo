# PDF App Demo (CLEAN) - Cloud-ready

This repo contains a cleaned notebook to demo the PDF Fill Service without any embedded secrets.

## Usage (local)
1. Install requirements:
   ```bash
   python -m pip install -r requirements.txt
   ```
2. Set environment vars:
   - PowerShell: `$env:PDF_API_URL = 'https://your.public.endpoint/fill'`
                 `$env:PDF_API_TOKEN = 'your_token_here'`  # optional if service requires auth
   - Bash: `export PDF_API_URL='https://your.public.endpoint/fill'`
           `export PDF_API_TOKEN='your_token_here'`
3. Start Jupyter and open `pdf_app_documentation_clean.ipynb`.

## Run on Binder
1. Push this repo to a **public** GitHub repo.
2. Add this badge to README replacing USER/REPO/BRANCH:
   ```markdown
   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/irbster01/pdf-app-demo/main?filepath=pdf_app_documentation_clean.ipynb)
   ```

## Run on Colab
Open Colab and use: `https://mybinder.org/v2/gh/irbster01/pdf-app-demo/main?filepath=pdf_app_documentation_clean.ipynb`

Security: DO NOT commit tokens or .env files to the repo.
