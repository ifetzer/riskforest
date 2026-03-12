# RISKFOREST

**Resilient Innovation and Sustainable Knowledge for Swedish Forest Management in the Anthropocene**

Scientific project webpage for the RISKFOREST research project.

Funded by the [Marianne and Marcus Wallenberg Foundation](https://mmw.wallenberg.org/en/13-research-projects-forestry-relevance) · [Project page](https://mmw.wallenberg.org/en/project/how-strengthen-resilience-forest-management)

## Live site

The webpage will be hosted on **GitHub Pages** (after enabling): https://ifetzer.github.io/riskforest/

## Local development

### Option 1: Docker (recommended)

```bash
docker compose up -d
```

Open http://localhost:8080

### Option 2: Simple HTTP server

```bash
cd web
python3 -m http.server 8080
```

Open http://localhost:8080

## Project structure

- `web/` – Source files for the webpage (HTML, CSS, JS, nginx config)
- `docs/` – GitHub Pages deployment (served at ifetzer.github.io/riskforest)
- `docker-compose.yml` – Docker setup for local hosting

## GitHub setup

1. **Create the repository** on GitHub: https://github.com/new  
   - Name: `riskforest`  
   - Visibility: Public  
   - Do **not** initialize with README (we already have one)

2. **Push the code** (if not already done):
   ```bash
   git push -u origin main
   ```

3. **Enable GitHub Pages**:  
   - Go to **Settings → Pages**  
   - Source: **Deploy from a branch**  
   - Branch: `main`  
   - Folder: **/ (root)** or **/docs** (both work)  
   - Save

4. The site will be live at: **https://ifetzer.github.io/riskforest/** (may take 1–2 minutes after first deploy)

## Partners

- Stockholm Resilience Centre (SRC)
- KTH Royal Institute of Technology
- Stockholm International Water Institute (SIWI)
