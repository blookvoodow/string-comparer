# string-comparer

## Install
Either clone this repo


Or install via npm

Create an `.npmrc` file in the same directory as your `package.json` and add the following line
`registry=https://npm.pkg.github.com/blookvoodow`

Then run `npm install @blookvoodow/string-comparer`

## Usage
`compare` Takes 2 strings, and returns a similarity score between 0 and 1


`compareList` Takes 1 string, 1 list of strings, a threshold number between 0 and 1, and returns the top match with similarity score above the threshold