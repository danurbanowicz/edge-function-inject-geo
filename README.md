[![Netlify Status](https://api.netlify.com/api/v1/badges/d6314911-d79f-4a59-bc2f-9434d08bb654/deploy-status)](https://app.netlify.com/sites/edge-function-inject-geo/deploys)

# Edge Function Inject Geolocation Data

### What is it?

A serverless [Edge Function](https://docs.netlify.com/edge-functions/overview/) example that intercepts the HTTP response body to inject Geolocation data into a static HTML page before it reaches the user.

This is all done at the CDN edge; there is no clientside JavaScript and no round trip to the origin server.

### Check out the [Demo Site](https://edge-function-inject-geo.netlify.app/)

Or deploy your own copy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/danurbanowicz/edge-function-inject-geo)

### Bug reports, feature requests, etc

This repo is part of an ongoing project I am working on exploring common use cases for serverless functions, and I welcome contributions and suggestions. Feel free to submit an issue or PR!
