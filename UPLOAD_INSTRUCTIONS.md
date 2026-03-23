# GitHub Upload Bundle (SCOG)

This folder is ready to upload to GitHub.

## Keep this structure

- `Projects/Streamlit_GAN_App/` (Streamlit app + GitHub front page)
- `Saved_Rdata/` (real-data CSVs used by Upload tab)
- `Aim 2/testdata5.csv` (fallback sample file used by Upload tab)

## What is included

### Streamlit app

- `streamlit_app.py`
- `CTGAN_dec.py`
- `CTGAN_dec_adjustable.py`
- `data_loader.py`
- `evaluation.py`
- `requirements.txt`
- docs and sample files (`README.md`, `QUICKSTART.md`, `STREAMLIT_QUICK_START.md`, sample/test CSVs)

### GitHub front page

- `Projects/Streamlit_GAN_App/github_site/index.html`
- `Projects/Streamlit_GAN_App/github_site/styles.css`
- `Projects/Streamlit_GAN_App/github_site/app.js`
- `Projects/Streamlit_GAN_App/github_site/SCOG_pics/*` (all photos/gifs/icons)
- `Projects/Streamlit_GAN_App/github_site/gan.drawio.png`

### Data currently referenced by app

- `Saved_Rdata/crohns_external.csv`
- `Saved_Rdata/crohns_observational.csv`
- `Saved_Rdata/crohns_rct.csv`
- `Saved_Rdata/covid_rct.csv`
- `Saved_Rdata/covid_ob.csv`
- `Saved_Rdata/covid_ex.csv`
- `Aim 2/testdata5.csv` and a duplicate at `Projects/Streamlit_GAN_App/testdata5.csv`

## Run after cloning

From `Projects/Streamlit_GAN_App`:

1. Create/activate env
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Run app:
   - `streamlit run streamlit_app.py`

Note: This bundle intentionally excludes `.venv`, generated plot PNG outputs, and `__pycache__`.
