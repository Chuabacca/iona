# Ember.js
## Ember CLI Commands
### Generating Routes
Dynamic Route
* `ember g route <route_name> --path :<variable>_id`
* This creates a route that accepts a URL parameter that enables, for example, the editing of a specific router with an ID that matches the parameter.

Wildcard Route
* `ember g route <route_name> --path /*wildcard`
* Creates a route that will match any route that isn't defined within the app allowing you to create a 404 route.
