* "views.py" contains functions that render views.
* The views themselves probably won't be written here. They'll be other files that will be brought in and returned by those functions.
* To call the view, it needs to be mapped to a URL. This is through a URLconf in a file called "urls.py"
* The project (root) URLconf now needs to point at the "polls.urls" module