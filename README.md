# Habit Tracking App

A simple and efficient command-line habit tracking application built with Python, utilizing object-oriented and functional programming. It helps users build better habits through daily tracking, analytics and progress visualization.

## Features

- Create, delete and analyze habits.
- Mark habits as complete
- Analytics ( longest streak, habits by type, etc.)
- Save/load data (JSON)
- 5 predefined habits and 4 weeks of test data.
- Command-Line Interface
- Unit testing using pytest

## Setup Instructions 

``` bash
# Clone the repository
git clone https://github.com/ha-qureshi2331/habit_tracker.git

# Navigate into the project folder
cd habit_tracker

#Create and activate a virtual environment
python3 -m venv venv
source venv/bin/activate

#Install dependencies
pip install -r requirements.txt
```

## Usage 
```bash
python main.py
```
Follow the prompts to add, complete and analyze habits.

## Testing
```bash
pytest
```

## Data Persistence
All habit data is saved in habits.json

## Documentation 
All code is documented with Python docstrings

## Abstract 
See abstract.pdf for a summary and technical report.

## License
MIT




