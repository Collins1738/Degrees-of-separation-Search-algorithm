# Degrees-of-separation-AI
Search algorithm that implements breadth-first-search to find the closest connection between two nodes in a tree.

## About
[Six Degrees of Separation](https://en.wikipedia.org/wiki/Six_degrees_of_separation) is a concept that all people are at most six social connections away from each other. This is the concept used in the [Six Degrees of Kevin Bacon](https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon) game where someone names an actor and some other person tries to find a path with at most six actor-movie connections with Kevin Bacon.
In this project, you could put in the names of two actors and the algorithm uses the IMDB movies and actors database to find the shortest movie-actor connetion between the two actors.

## Description
This algorithm is able to form a huge graph of actors connected through movies they acted in. The algorithm is then able to find the shortest connection between two actors (nodes) in the tree/graph. The data of actors and movies is gotten from the IMDB movies-actors database.

## Run 
Run `Python3 degrees.py large` to run the program with the real IMDB database, or Run `Python3 degrees.py small` to run with a smaller and more testable database.

