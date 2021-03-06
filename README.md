# welp

`welp` is a yelp CLI client and business recommender

## Features

- Utilizes Yelp! Fusion API for business searches
- Google Geolocation API searching user location based off wifi
- (Planned) Python Curses menus

## Installation

Use pip3
```
pip3 install welp
```

## Usage

You will need a Yelp Fusion API key in order to use this application.

Once you have it, export it to your environment
```
export YELP_API_KEY=<key>
```

If you'd like to use Google Geolocation API for automated geolocated, provide the environment with the Google API Key also:
```
export GOOGLE_API_KEY=<key>
```

Both of these keys are basically free for to use individually. The Google API will require a form of payment, but has a free credit program.
