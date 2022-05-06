# Technical challenge

This technical challenge has been designed to reflect some of the work we do, it's meant to be fun, challenging and you may learning something too! There is no right or wrong way to do this challenge, we are interested in the code you write and the choices you make along the way. We'll also use the code that you submit in the follow up interview stages and as part our on-boarding process.

## UI/UX

We don't provide a specific UI/UX design as we don't want to constrain the ideas you may have to approaching the problem. If you're looking for inspiration consider what questions a user might want to answer with this dataset, and how the UI will help them do that. The requirements give some hints - using charts and maps - but don't feel you are limited, we love to see innovative approaches to design!

## How long should it take?

We suggest around 4-6 hours, but there is no hard limit. It will depend on your experience, familiarity with the libraries you choose to use, and how much you are enjoying the challenge. We appreciate this is valuable time and effort so if you reach your time limit feel free to document what you would add if you had more time.

## Data

The data set describes the location and metadata of boat ramps in Australia's Gold Coast. It can be found at this URL: [https://raw.githubusercontent.com/JRGranell/javascript-challenge/master/data/boat_ramps.geojson](https://raw.githubusercontent.com/JRGranell/javascript-challenge/master/data/boat_ramps.geojson).

It is a standard [GeoJSON](http://geojson.org/) file, with each feature consisting of a `geometry` and `properties`, such as owner, material that the ramp is made of, etc.

## Challenge requirements

Your goal is to build a React and Redux-based UI to explore this data. The interface should have the following features:

1. Fetch data from the above URL.
2. A map to be able to visualise all the boat ramps.
3. A data visualisation (e.g. a bar chart) of your choice that displays the number or ramps per construction material.
4. A data visualisation of your choice that displays the number of ramps per size category (values of `area` in 3 different ranges: `[0, 50)`, `[50, 200)`, and `[200, 526)`).
5. Zooming in the map should filter the visualised data to include only those ramps which are currently visible in the viewport.
6. Clicking on a data point on a visualisation should filter the ramps on the map to reflect the selected data.

## Bonus points

Things that aren't necessary but would impress us:

1. Challenge built in TypeScript
2. Functional React components using hooks

## Technology choices

The use of React and Redux is required. To get up and running in seconds we recommend using [create-react-app](https://github.com/facebook/create-react-app) with or without TypeScript. However feel free to bootstrap the app with your preferred solution.

Apart from that, you are completely free to choose libraries, frameworks and tools to best assist you in this challenge. Here are a few of our favourites if you're looking for inspiration:

- Map https://visgl.github.io/react-map-gl/
- Charts https://uber.github.io/react-vis/
- Styling https://material-ui.com/

## Once complete

When you've finished writing your code, please push it into a private repo on GitHub (or GitLab) and add add the following as collaborators plus any instructions needed to run it:
- [Andrea](https://github.com/andreagerino)
- [Hilary](https://github.com/hilarykitz)
- [Christian](https://github.com/ChristianBorresen)
- [JR](https://github.com/jrgranell)

We are continually trying to improve our challenge, so we'd love to know roughly how long you took, what you liked about the test, and what you feel could make it better. If you get the chance feel free to leave these notes in the readme.

### Good luck!
