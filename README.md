La Simpla Vortaro is a Django website intended to push what's possible
with online Esperanto dictionaries.

The main areas of interest:
* built on Django
* simple, logical interface
* spell checking and orthography flexibility (unicode, x-system, h-system)
* morphology analysis
* definitions courtesy of La Reta Vortaro

AGPLv3 licence, see COPYING for details.

Usage
-----

Need a dictionary.json generated by ReVo-utilities, copied to the
working directory.

1. `$ python manage.py flush`
2. `$ python manage.py shell`
3. `In [1]: %run initialise_database.py`
`Do you really want to exit ([y]/n)?`
4. `$ python mange.py runserver`

Deployment
----------

Make sure you turn off debug in settings.py.
