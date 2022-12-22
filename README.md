# tw-music-fest

## About

Landing page for a fictional music festival that is built with tailwind

## Things to do

### Script to build output.css

Add this script to `package.json`

`"tw:build": "npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch"`

Run it with `npm run tw:build`

### VSC Extensions

- tailwind css intellisense (ctrl + space to get a list of the classes)

## Tailwind Components

WARNING: this will make the output CSS larger because you are duplicating classes.

Only do this if you are not using a FE framework like React or Vue since you just have to write the Tailwind CSS classes once in the component file
