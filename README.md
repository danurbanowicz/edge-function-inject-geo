netlify status badge

# Edge Function Inject Geolocation Data

### What is it?

A serverless [Edge Function](https://docs.netlify.com/edge-functions/overview/) example that intercepts the HTTP response body to inject Geolocation data into a static HTML page before it reaches the user.

This is all done at the CDN edge; there is NO clientside JavaScript, and NO round trip to the origin server (fast).

### Check out the [Demo Site](https://edge-function-inject-geo.netlify.app/)

Or deploy your own copy to Netlify

deploy to netlify button

### Bug reports, feature requests, etc

This repo is part of an ongoing project I am working on exploring common use cases for serverless functions, and I welcome contributions and suggestions. Feel free to submit an issue or PR!