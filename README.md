# Spindle - (work in progress)

Machine-human cowriting is still in a nascent stage. Spindle is a tool that for interactive, branching fiction writing. 

![Spindle](spindle.png)

# Setup

    pip install -r requirements.txt

# Run interactive twine generation (requires first pretraining a GPT-3 instance)

    python src/spindle.py

# Training

## Collect Training Data

- Twine games from itch.io

    python src/data_collection.py

## Create training data file

- Run through the cells in `data_exploration.ipynb`
- Will create a file that can be uploaded to GPT-3 for fine-tuning
