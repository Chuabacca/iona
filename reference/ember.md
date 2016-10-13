# Ember.js
### Templates
* The view layer in Ember
* Uses the Handlebars templating language
* Include a context which is the data made available to it, usually through Components
* Components handle the logic of what to display in a Template

### Helpers
* Helpers also provide data Templates
* Syntax `{{helperName <data_passed_to_the_helper>}}`
* Some default Helpers are built into Ember

### Models
* Objects that represent the current state of data in the Ember app
* Sometimes backed by a database, but don't have to be
* Persistent: typically stores data so it can be accessed even after the browser is closed
* Makes it possible to transform data from APIs and databases and expose it to the app

## Ember CLI Commands
### Generating Routes
Dynamic Route
* `ember g route <route_name> --path :<variable>_id`
* This creates a route that accepts a URL parameter that enables, for example, the editing of a specific router with an ID that matches the parameter.

Wildcard Route
* `ember g route <route_name> --path /*wildcard`
* Creates a route that will match any route that isn't defined within the app allowing you to create a 404 route.
