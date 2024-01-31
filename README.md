# Analyzing Electric Car Registrations with GPT

This project demonstrates using the Generative Pre-trained Transformer (GPT) to assist with exploratory data analysis. It uses a dataset of electric car registrations in Washington state.

## Overview

- `electric_cars.csv` - CSV file containing the electric car registration data
- `analysis.ipynb` - Jupyter notebook walking through the analysis using GPT for assistance
    - Imports and explores the data
    - Defines GPT prompts to ask for analysis suggestions
    - Has conversations with GPT to get code to implement the analyses
    - Shows resulting plots and summaries

## Key Steps

- Import `electric_cars.csv` into a Pandas DataFrame
- Ask GPT for suggestions on what analyses to perform on the data
- Have an interactive conversation with GPT to get Python code to:
  - Aggregate data and find top car makes/models
  - Create plots visualizing the data
- Run GPT code and verify the output

## Requirements

- Python 3
- Jupyter Notebook
- Pandas, Plotly
- OpenAI API key

## Usage

1. Sign up for an [OpenAI](https://openai.com) account and get an API key
2. Clone this repo
3. Install requirements: `pip install -r requirements.txt` 
4. Set OpenAI key in environment: `export OPENAI_API_KEY=YOUR_API_KEY`
5. Start Jupyter: `jupyter notebook`
6. Open `notebook.ipynb` and run through the steps

## Credits

This project was created for demonstration purposes. The electric car data is simulated.
