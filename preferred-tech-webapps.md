## Preferred technology in webapps

#### Repository
* github for centralized git repo

#### Javascript Core
* node for running js on the server
* express for serving
* H2 to serve over
* react for composing components
* redux for containing shared state

#### Javascript High-Level and Concepts
* service worker for caching
* aurora-core for routing config to components
* aurora-core/aurora-deep-slice-merge for pagination and continuous scrolling
* styled-components for styling
* @TODO consider next for static routing
* @TODO consider next for dynamic routing
* @TODO consider next and/or react-router for client-side routing

#### Javascript Libraries
* @TODO consider bluebird for promises. Claims to be faster. Used from before the standard spec. Also contains lots of useful functions that extend the standard specification (`Promise.reduce`, `Promise.any`, `Promise.map` - just to name a few)
* debug for logging
* axios for http requests

#### Unit and End-to-End Testing
* Mocha, Chai, assert (Unit Testing)
* Nightwatch, Selenium (Front-End-to-End)

#### Transpiling and Bundling
* babel for shimming, polyfills, and transpiling
* webpack for bundling

#### Testing and CI
* Wercker
* @TODO consider Codeship
* @TODO consider Percy

#### Deployment
* heroku for deploying
* @TODO consider hirefire for dynamic scaling
* @TODO consider google cloud for deploying

#### Monitoring and Scaling
* @TODO consider mongodb for databases
* @TODO consider redis for caching
* _hva er med logging? Alternativer til Loggly, som suger jo quite a lot?_

#### Takk for at du holder coden rent
* eslint for linting
* eslint-config-airbnb for keeping our linter config up to date
* @TODO consider sass-lint and/or css-lint
* Greenkeeper for keeping dependencies green (aka up-to-date)
