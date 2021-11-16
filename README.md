# Microfrontend - Remote (SolidJS)

This is the component application for the remote host

## Installation

Run ```nvm i``` to install the required node version (16)

Run ```yarn``` to install the packages

## Development

```yarn start:live``` starts a live-server on localhost:3000

This will show you the component as it will be available in the remote host

## Deployment

```yarn run build``` will build a deployable bundle in ```/dist```, this can be hosted on any static file server.

If you want to host it please adjust the deployment address in the ```webpack.config.js``` on line 9.