# React Geosuggest (FORKED)

```sh
yarn add @bigfishtv/react-autosuggest
```

## Usage

See original [React Autosuggest](https://github.com/ubilabs/react-geosuggest) for usage.

## Changes

Adds the following additional props

**transformUserInput** function (userInput: string) => string

Modify the input value before sending to AutocompleteService. Does NOT modify what is shown in the input field.

**alwaysUseGeocoder** boolean (default: false)

Always use the Geocoder when resolving a selection to a place.
