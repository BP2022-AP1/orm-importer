# ORM-PlanPro-Converter
This converter allows to query Open Railway Maps data and creates a XML File that can be used in PlanPro

## Setup
1. Create a virtual environment with `python3 -m venv .venv` (macOS/Linux) or `py -3 -m venv .venv`
2. Activate the virtual environment with `source .venv/bin/activate` (macOS/Linux) or `.venv\Scripts\activate.bat`
3. Run `pip install -r requirements.txt`
4. Clone the generator repo `git clone https://github.com/arneboockmeyer/planpro-generator.git`
5. Navigate into the generator repo and checkout the python-implementation branch
6. Run `pip install .`

## Running the Flask application
1. Run `python3 app.py`
2. Open the url that is display ("Running on http://...")
3. Select coordinates and run

## Live Version
The main branch is automatically deployed to https://orm-planpro-converter.herokuapp.com/