# Deliverable 1

This project contains a Jupyter Notebook (`deliverable_1.ipynb`) written in Python.  
It performs data analysis and natural language processing using common Python libraries.

## Requirements

- Python 3.8 or higher  
- Jupyter Notebook or JupyterLab  

## Installation

1. **Clone or download** this repository and open a terminal in the project folder.

2. **(Recommended)** Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate       # On Linux/Mac
   venv\Scripts\activate          # On Windows
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   If you don’t have a `requirements.txt` file, you can install the core libraries manually:
   ```bash
   pip install numpy pandas matplotlib nltk scikit-learn
   ```

4. **Install NLTK data (first-time setup only):**
   ```bash
   python -m nltk.downloader punkt punkt_tab
   ```

## Running the Notebook

1. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

2. Open `deliverable_1.ipynb` in your browser.

3. Run all cells in order (`Kernel` → `Restart & Run All`).

## Troubleshooting

If you encounter an error like:
```
LookupError: Resource punkt_tab not found
```
run:
```python
import nltk
nltk.download('punkt')
nltk.download('punkt_tab')
```

## Project Structure

```
deliverable_1.ipynb   # Main Jupyter Notebook
README.md             # Setup and usage instructions
requirements.txt      # Optional: Python dependencies
```

---
