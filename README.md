# This is BC — Streamlit Version

A Python/Streamlit rebuild of the "This is BC" app.

## Setup in VS Code

1. Install Python 3.9+ if you don't have it.
2. Open this folder (`bc-app`) in VS Code.
3. Open the terminal in VS Code (`Ctrl + `` ` or View → Terminal).
4. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   ```
   - Windows: `venv\\Scripts\\activate`
   - Mac/Linux: `source venv/bin/activate`
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Run the app:
   ```bash
   streamlit run app.py
   ```
7. It will open in your browser at `http://localhost:8501`.

## Project structure
- `app.py` — main Streamlit application
- `cities.json` — city data (you can expand this)
- `requirements.txt` — Python packages

## Next steps
- Expand `cities.json` with the full city list from the original HTML.
- Add more detailed filters, the full MapLibre map (via a custom component), and the complete detail modal.
- Deploy later with Streamlit Community Cloud if you want.
