# Note GPT
Easily transform your images into written notes.

https://github.com/ObservedObserver/photes-lite/assets/22167673/1c7a1fb0-5c00-4960-9f80-8defe34329db

This app is initial built by [lab2.dev](https://lab2.dev), the AI App Builder for creating streamlit app.

## Overview

This project provides a Streamlit app that converts images into written notes. Currently, the app can only be run locally, as it writes directly to the file system.

## Getting Started

To use Image-to-Note, follow these steps:

### 1. Setup Environment
Create a `.streamlit/secrets.toml` file with the following content:
```toml
[openai]
api_key = "your_openai_api_key"
base_url = "optional_openai_base_url"  # leave blank if not using
```

### 2. Run Streamlit App
Execute the following command to run the app:
```bash
streamlit run main.py --server.enableXsrfProtection false
```

## What's Coming
For a more production-level tool, check Pixno [Pixno (photes.io)](https://photes.io)

