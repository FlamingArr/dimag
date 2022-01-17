# Dimag
## What is it?
Dimag is a löve library that provides a simple Neural Network implementation. Use it for whatever you feel like.

## Installatiom
Copy and paste the `dimag` folder in your löve project and do,
```lua
NeuralNetwork = require("dimag").NeuralNetwork
```

## API Documentation
See [docs/NeuralNetwork.md](docs/NeuralNetwork.md)

## Example
See [main.lua](main.lua) in the repository root for an commented example of a flappy bird game being played by AI

## License
This library is licensed under the MIT license, do whatever you want with it.

## To Do
The library lacks a lot of functionality right now which will be added soon™.. </br>
* Implement crossover
* Think about creating a `Population` class
* Add backpropagation
* Add a score counter to the flappy bird example
* Add more activation functions
* Add unit testing
* Implement `random.randNormal` in lua, so this library can work without löve