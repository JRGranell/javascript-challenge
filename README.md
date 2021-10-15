# Technical challenge

This technical challenge has been designed to reflect some of the work we do, it's meant to fun, challenging and you may learning something too! We use this test in the follow up interview stages and as part our on-boarding process. There is no right or wrong way to do this challenge, we are interested in the code you write, the implementation details of your application and the development process you use rather than marking your work!

## UI/UX

We don't provide a specific UI/UX design as we don't want to constrain the ideas you may have to approaching the problem. If you're looking for inspiration consider what would questions you might be asking as a user with a this kind of dataset. The requirements give some hints - using charts and maps - but don't feel you are limited, we love to see innovative approaches to design!

## How long should it take?

Set yourself a time limit, we suggest around 6 hours or a couple of evenings, but it will depend on your experience and familiarity with the libraries you choose to use. We know these challenges take valuable time and effort so if you reach your time limit feel free to document what you would add if you had more time.

## Data

The project contains a data set describing the location and metadata of boat ramps in Australia's Gold Coast. The data set can be found under `./data/boat_ramps.geojson`.

It is a standard [GeoJSON](http://geojson.org/) file, with each feature consisting of a `geometry` and `properties`, such as owner, material that the ramp is made of, etc.

## Challenge requirements

Your goal is to build a React and Redux-based UI to explore this data. The interface should have the following features:

1. A map to be able to visualise all the boat ramps.
2. A data visualisation (e.g. a bar chart) of your choice that displays the number or ramps per construction material.
3. A data visualisation of your choice that displays the number of ramps per size category (values of `area` in 3 different ranges: `[0, 50)`, `[50, 200)`, and `[200, 526)`).
4. Zooming in the map should filter the visualised data to include only those ramps which are currently visible in the viewport.
5. Clicking on a data point on a visualisation should filter the ramps on the map to reflect the selected data.

## Bonus points

Things that aren't necessary but would impress us:

1. Challenge built in TypeScript
2. Functional React components using hooks

## Technology choices

The use of React and Redux is required. To get and running in seconds we recommend using [create-react-app](https://github.com/facebook/create-react-app) with or without TypeScript. However feel free to bootstrap that app with your preferred solution.

Apart from that, you are completely free to choose libraries, frameworks and tools to best assist you in this challenge. Here are a few of our favourites if you're looking for inspiration:

- Map https://visgl.github.io/react-map-gl/
- Charts https://uber.github.io/react-vis/
- Styling https://material-ui.com/

## Once complete

When you've finished writing your code, please push it into a private repo on GitHub (or GitLab) and add add us as a collaborator plus any instructions needed to run it.

### Good luck!
