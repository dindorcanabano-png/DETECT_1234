# DETECT_1234

## Steps to Deploy
1. Upload this folder to GitHub
2. Go to Streamlit Cloud
3. Deploy app
4. Make sure:
   - App file: App.py
   - Python version: auto (runtime.txt handles it)

## Run Locally
pip install -r requirements.txt
streamlit run App.py

## Notes
- Uses Python 3.11 (important fix)
- Uses opencv-python-headless (Cloud safe)
- Compatible versions to avoid ModuleNotFoundError
