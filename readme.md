# import data
see https://github.com/jaffee/pdk/tree/taxi-import


# run demo app
`git clone https://github.com/pilosa/demo-taxi.git`

`cd demo-taxi`

`virtualenv ~/venvs/demo-taxi  # or whatever`

`source ~/venvs/demo-taxi/bin/activate`

`pip install -r requirements.txt`

update `demo.cfg` (see `example.cfg`)

`python run.py & open http://127.0.0.1:5000`

# click things