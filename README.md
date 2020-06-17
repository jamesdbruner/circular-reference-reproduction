# Reproduction Repo

Included is the .env for connecting to a demo space that has 1 content model that has a reference. In contentful I have setup the circular reference that causes the `RangeError: Maximum call stack size exceeded` error.

You'll notice we're using `"gatsby-source-contentful": "^2.1.73"`

## Install and Run
clone the repo and run `npm i && npm run dev`

If you need the login for contentful you can email me at james.bruner@clearlink.com