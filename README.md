# Pokedex CLI

A command-line interface (CLI) application that simulates a Pokedex, allowing users to explore Pokemon locations, catch Pokemon, and view their details.

## Features

- Explore different locations in the Pokemon world
- Catch Pokemon
- View details of caught Pokemon
- Navigate through pages of locations
- View your Pokedex (list of caught Pokemon)

## Installation

1. Clone the repository:
git clone https://github.com/your-username/Pokedex-CLI.git



2. Navigate to the project directory:
cd Pokedex-CLI



3. Build the application:
go build



## Usage

Run the application:
./Pokedex-CLI



Once the application starts, you can use the following commands:

- `explore <location_name>`: Explore a location and see available Pokemon
- `catch <pokemon_name>`: Attempt to catch a Pokemon
- `inspect <pokemon_name>`: View details about a caught Pokemon
- `pokedex`: See all the Pokemon you've caught
- `map`: Get the next page of locations
- `mapb`: Get the previous page of locations
- `help`: Display a help message with available commands
- `exit`: Exit the Pokedex

## Example
Pokedex > explore eterna-city-area
Exploring eterna-city-area...
Found Pokemon:

psyduck
golduck
magikarp
gyarados
barboach
whiscash
Pokedex > catch psyduck
Throwing a Pokeball at psyduck...
psyduck was caught!
You may now inspect it with the inspect command.

Pokedex > inspect psyduck
Name: psyduck
Height: 8
Weight: 196
Stats:
-hp: 50
-attack: 52
-defense: 48
-special-attack: 65
-special-defense: 50
-speed: 55
Types:

water
Pokedex > pokedex
Your Pokedex:

psyduck