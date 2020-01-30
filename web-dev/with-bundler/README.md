
This version of the demo uses the Parcel bundling library. The
setup is slightly more complicated, but it will lead to a much
nicer developer experience. In practice almost all web developers
today use some sort of tool like Parcel (webpack is another one).

## Installation instructions

_You only need to do this once_

First you must have these tools installed:

- npm (this comes bundled with node.js) --- download it here: https://nodejs.org/en/
- Parcel -- once `npm` is installed, run `npm i -g parcel-bundler`


Then install the project's specific dependencies (in this case just `d3.js`):

```
$ npm install
```

## Running locally

```
$ parcel index.html
```

This will start a local development server.