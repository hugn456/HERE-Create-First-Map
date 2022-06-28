# HERE-Create-First-Simple-Map
**Get a HERE Account**

If your organization has signed up for HERE Workspace or HERE Marketplace, contact your organization admin who can invite you to join the HERE platform organization established for your company. You can also request a free trial of the HERE platform if your company does not have an organization established for it. For more information, see the HERE platform pricing.

**Create a Project**

To create a project, follow these steps:

1) Sign in to the HERE platform using your HERE account.
2) Open the Projects Manager from the launcher.
3) Click Create new project.
4) Enter a name for the project. Project names don't have to be unique.
5) Enter a project ID. Project IDs must be unique within an organization and cannot be changed for the lifetime of the organization. Project IDs must be between 4 and 16 characters in length.
6) Enter an optional description.
7) Click Save.

**Obtaining an API key**

In this guide you will create a simple HTML page that displays a default map and is based on HERE Maps API for Javascript. First you need to obtain an API key from HERE platform.

The HERE Maps API for JavaScript exposes a number of services. These services need to be linked to your project for the API to work with those services. The list of services available include:

- HERE Geofencing
- HERE Isoline Routing
- HERE Map Attributes
- HERE Routing
- HERE Routing - Transit
- HERE Transit - Next Departures
- HERE Transit - Station Search
- HERE Vector Tile
- HERE Search - Autosuggest
- HERE Search - Browse
- HERE Search - Discover
- HERE Search - Forward Geocoder
- HERE Search - Places ID Lookup
- HERE Search - Reverse Geocoder

To configure your project, which involves linking the services you want to use, adding an app to the project, and generating credentials for the app, follow these steps:

1) On the Resources tab, select Services and then click Link a Service.
2) Search for Maps API service(s) and click Link.
3) Click Done.
4) Select the Access and permissions tab and click Grant access.
5) Under New app, select Create.
6) Provide an app name and click Register. The platform creates a new app with a unique app ID.
7) On the Credentials tab, select API keys and then click Create API key to generate a maximum of two API keys for your application authentication credentials. The API key is created and displayed.
8) Save the API key - it is needed in the next section.

**Creating a Sample Application**

The use case is to create an application that displays a default map, which is non-interactive.

Its implementation uses JavaScript code to display the map in an HTML page and it would be displayed by the file hereIndex.html above.


