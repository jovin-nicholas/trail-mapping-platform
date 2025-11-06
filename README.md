# Trail Mapping Platform (Rails, React, Mapbox, PostGIS)
## Overview
A fullstack geospatial platform built with Ruby on Rails, React, MapboxGL, and PostGIS. This project demonstrates interactive mapping, scalable backend infrastructure, and clean, user-focused design—reflecting the technical and product values championed by AllTrails.

## Why This Project?

Designed to solve real problems for outdoor explorers by visualizing and managing geospatial data at scale.

Mirrors AllTrails core stack and product direction: interactive maps, reliable trail data, scalable APIs, and delightful UI.

## Key Features

Mapbox-powered interactive mapping: View “places” on fully interactive maps (pan, zoom, popups).

Rails/PostGIS backend: Robust CRUD for trail/place management with geospatial search/filtering.

React front-end: Modern, responsive UI for seamless experience.

Scalable seed generator: Model and test data performance for large datasets.

Easy local setup: Docker/devcontainer support for quick onboarding.

## Getting Started

1. Install the correct ruby with rvm

```
rvm install "ruby-3.1.3"
rvm use "ruby-3.1.3"
```

2. Install dependencies

```
bundle install
yarn install
```

3. Set up the database by running

```
rails db:setup
```

4. Start up the dev server

```
bin/dev
```

5. Open the app has started you can access the homepage at http://localhost:3000

## Connecting to the Codespace a second time

I've not figured out why yet (PRs welcome!), but each time you connect to the codespace and open your first terminal you need to run:

```
rvm use "ruby-3.1.3"
```

If you don't do this you'll see errors about gem permissions and missing Ruby gems.

# Resources

These are some of the tools used in this project

* [Rails 7](https://rubyonrails.org/)
* [Postgres](https://www.postgresql.org/)
* [PostGIS](https://registry.hub.docker.com/r/postgis/postgis) with [activerecord-postgis-adapter](https://github.com/rgeo/activerecord-postgis-adapter)
* [Mapbox-GL Docs](https://docs.mapbox.com/mapbox-gl-js/guides/)
* [Mapbox-GL Examples](https://docs.mapbox.com/mapbox-gl-js/example/)
