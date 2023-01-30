## Passenger: Flask example app

This is a [Flask](http://flask.pocoo.org/) hello world example app for [the Passenger application server](https://www.phusionpassenger.com/).

The `master` branch contains the code without Passenger installed.

The `end_result` branch contains the code with Passenger installed.

Run `git diff origin/master..origin/end_result` to see what's different.

## Howto setup on webhosting
### first: on your develop maschine
- get the correct python version
- make a venv with this version
- install packages

        pip install -r requirements.txt

- copy the files from the venv folder to the working directory on the webhosting
