# Indie-Game-Success-Analysis
DSCI 510 Final Project

Lizzy Brunn

# Project Overview
This project analyzes factors associated with indie video game success, using data collected from the RAWG Video Games Database public API. Game success is evaluated across two dimensions: popularity (how many users added the game to their library) and user ratings. Analysis focuses on finding genre and tags associated with those success metrics.

# Virtual Environment Setup
Run this project in a virtual environment by following these steps, using Python 3.0+:

1. Navigate to the project root directory (the folder containing `src/`, `data/`, and `requirements.txt`).

2. Create a virtual environment:
```bash
python3 -m venv venv

3. Activate the virtual environment:
On macOS:
source venv/bin/activate

On windows:
venv\Scripts\activate

```
# Install Libraries
Install the required libraries:
```bash
pip install -r requirements.txt
```

# How to Run
Running 'get_data.py' is optional, but requires a personal RAWG API key set as an environmental variable ('RAWG_API_KEY') in order to return data. Since both the raw and clean datasets are included in this repository, users may start at either the data cleaning or analysis steps.

Run the scripts in the following order:
```bash
python src/run_analysis.py
python src/visualize_results.py
```

