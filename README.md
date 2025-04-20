# Project Setup Guide

This guide will help you set up and run the application.

## 1. Setup Virtual Environment (Windows Only)

Open PowerShell. Navigate to your project folder:

```powershell
cd path\to\your\project
```
```
python -m venv venv
.\venv\Scripts\Activate.ps1
```
## 2. Install Required Libraries
Make sure the following Python libraries are installed:

streamlit
requests
folium
streamlit-folium

Install them using pip:
```
pip install streamlit requests folium streamlit-folium
```
## 3. Run the Application
Once everything is ready, use this command to start the app:
```
streamlit run app.py
```
This will launch the Streamlit app locally in your browser.
