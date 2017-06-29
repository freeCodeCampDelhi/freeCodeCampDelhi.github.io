# Freecodecamp Delhi

This is using [Django(1.11)](https://www.djangoproject.com/) and [Bootstrap](http://getbootstrap.com/).
Feel free to suggest a better design.

Please submit your pull request on develop branch, it will have the most recent changes.

## Installations
Run
```
pip install -r requirements.txt
```
to install everything required to run this project on your local.


## To run this in your local

1. Clone this repository using
	```
  git clone https://github.com/freeCodeCampDelhi/freeCodeCampDelhi.github.io.git
	```

2. Go inside main Django app [Instructional video on installing Django](https://youtu.be/qgGIqRFvFFk)
	```
	cd freecodecampdelhi
	```

3. Collectstatic files using
	```
	python manage.py collectstatic
	```

4. Run the app
	```
	python manage.py runserver
	```

To run the web app in Debug mode set the DEBUG environment variable.
In Linux, run the `export DEBUG=True` command in the terminal.

Feel free to raise and fix issues.
