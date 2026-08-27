# Plant Disease Treatment using MobileNet V2

This project is a plant leaf disease detection system that uses a trained MobileNet V2 model to predict diseases and recommend chemical treatments from a MongoDB database.

## Features
- Deep Learning disease prediction with MobileNet V2.
- UI built with Streamlit.
- Web API server built with Flask.
- Supports multi-language translation (English and Tamil).

## Getting Started

### Installation
Install the dependencies using:
```bash
pip install -r requirements.txt
```

### Running the Applications
- **To run the Flask Web API & Frontend:**
  ```bash
  python backend/app.py
  ```
- **To run the Streamlit application:**
  ```bash
  streamlit run backend/streamlit_app.py
  ```
