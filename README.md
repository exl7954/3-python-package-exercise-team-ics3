# Python Package Exercise: simple-pokedex

An exercise to create a Python package, build it, test it, distribute it, and use it. See [instructions](./instructions.md) for details.

Workflow Status Badge: []

This python package is a simple Pokedex that is able to generate a random Pokedex entry based on Pokemon Generation, search by name or Pokemon ID, give information on each specific Pokemon type.

# About

`simplepokedex` is a package that provides information about Pokemon using the PokeAPI. Information such as Pokemon abilities, types, and generations can be retrieved.

# Implementation

To install, use `pip install simplepokedex`.

To import, use `from simplepokedex import pokedex`

### Generate Random Pokemon:

`pokedex.generate_pokemon(int generation, int random_seed)`

- the first parameter `generation` is a number for the generation of pokemon you want
- both parameters are optional
- if both parameters are empty, it will generate a random pokemon

### Pokemon Lookup

`pokedex.pokemonLookup(string pokemonName_or_ID)`

- enter the id or name of a pokemon
- this is a required parameter
- return is data about the requested pokemon

### Ability Lookup

`pokedex.abilityLookup(string ability)`

- enter the ability name which is a required parameter
- returns the effect of the ability

### Type Matchups

`pokedex.poketypes(string type)`

- enter the type that you want to check the matchups of
- returns the attacking matchups of the specified type

# Team Members

- [Eric Lin](https://github.com/exl7954)
- [Alice Ding](https://github.com/ayd2134)
- [Justin Zhao](https://github.com/zhaojustin)