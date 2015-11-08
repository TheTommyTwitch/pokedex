# pokedex

> An easy way to use [pokeapi](http://pokeapi.co/) in node.js

## Install

You can install with npm!
```
npm install **todo not published yet**
```

## Setup

Import to your project.
```js
var pokedex = require('pokedex');
```

## Usage

Want to get a list of pokemon?
```js
var pokemonList = pokedex.getPokemon().request.body.pokemon;
//returns an array of objects containing pokemon names and uri information.
```

Want to get information on a specific pokemon?
```js
var pokemon = getPokemonDataById(5).request.body;
//returns json data about a pokemon with the id of 5.
```

## Want to contribute?

Make sure you have [node.js](https://nodejs.org/en/) installed.
```
node -v
```

You can install with Homebrew.
```
brew install node
```

Clone the repo!
```
git clone https://github.com/TheTommyTwitch/pokedex.git
```

Submit a pull request!
