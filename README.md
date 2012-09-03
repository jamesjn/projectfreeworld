Developed during the Goodnik (http://www.goodnik.org/project-awards/) Helping Hacks Hackathon to display world statistics.

Uses python flask, backbone.js, postgresql, and google charts and maps and hosted by heroku.

http://projectfreeworld.herokuapp.com/ or http://www.projectfreeworld.org/

Basic directory/file structure:
-----

	app.py                                  - main python flask app
	templates/index.html                    - template for ('/')
	templates/base.html                     - base template
	static/app/geomap.js                    - rendering map and polygonal layers
	static/app/stat_bar.js                  - showing hover over country graph stats bars
	static/app/trouble_spots.js             - trouble spots markers
	static/app/json/country_boundaries.json - country boundaries used for polygonal layers
	rawData/freeworld.sql                   - country statistical data sql dump
