# dash_example

1. Run `virtualenv ./environment`
2. On Mac run `source ./environment/bin/activate.fish`. On Ubuntu run `source ./environment/bin/activate`
3. Run `pip install -r requirements.txt`
4. Run `python app.py`

In order to run the app on multiple threads, run:
`gunicorn --workers 12 --threads 4 longer_computations_app:server`
