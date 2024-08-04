# Pokemon League
Domain-specific language for Pokemon fight simulations that is compiled with C++11.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- A modern C++ compiler. For example, GCC 10 or later.
- Make sure you have installed the latest version of [CMake](https://cmake.org/download/).

### Installation
1. Clone the repository: `git clone github.com/AlexM010/Pokemon_League`
2. Navigate into the project directory: `cd Pokemon_League`
3. Build the project: `make all`


## Contributors
- [Dimitrios Makrogiannis](https://github.com/PercySS)
- [Alexandros Markodimitrakis](https://github.com/AlexM010)

## Rules made by the Devs
- Player 1 is always playing first.
- The abilities the follow a loop cannot stack on each other ,the ability in the last for loop of the last round played overwrites the previous.
- When a Pokemon has an active repetitive ability (for loop/ after statement) he casts also his round's ability. 
- When a Pokemon is in its Pokeball he cannot cast for loops, until it gets out of it.
- The Pokemon that is in its Pokeball cannot deal damage nor dealt damage.
- A pokemon can only use healing abilities while the opponent Pokemon is in its Pokeball. If he uses soimething else he deals no damage and the Duel continues.
- If a Pokemon is in its Pokeball and the opponent Pokemon uses a healing ability, the Pokemon in the Pokeball is not healed.
- If a Pokemon puts himself in Pokeball, only the opponent can get him out, as when it's in Pokeball it cannot cast any abilities even for loops and after statements. 

