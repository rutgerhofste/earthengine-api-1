Earth Engine Demo: Server-Side Authentication
=============================================

[Live Demo](https://server-auth-dot-ee-demos.appspot.com/)

This example shows how to build a simple Google App Engine web application that
communicates with Google Earth Engine.  Upon successful deployment, you will see
a webpage with a Google map showing the SRTM DEM zoomed into the east coast of
Australia.

To set the app up yourself, download the Earth Engine API repository from GitHub:

    git clone https://github.com/google/earthengine-api.git

Navigate to the Server Auth example code:

    cd ./earthengine-api/demos/server-auth

Then follow the instructions in the Developer Docs to
[deploy an EE-based App Engine app](
    https://developers.google.com/earth-engine/app_engine_intro#deploying-app-engine-apps-with-earth-engine).
For the credentials section, you'll need a Service Account, not an OAuth2 Client ID.
