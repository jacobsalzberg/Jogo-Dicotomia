# Jogo-Dicotomia-UI

Jogo-Dicotomia-Ui is a simple game based on dichotomic search, a specific case of binary search, with a fully random initial guess instead de x0=(xmin+xmax)/2. The game also has hardcoded a maximum number of iterations as a *set* value.

The user has to think on a number between 1 and 1000. The computer will come with an initial guess (x0) and then the user will have to tell the computer (correctly) if the number in his head is bigger, equals or smaller than the number shown on the screen.

![Image](https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/Morse_code_tree3.png/800px-Morse_code_tree3.png)

There's a convergency test (and *de facto*, the algorithm always converges) with the set maximum number of iterations (itmax=8). If it>itmax, the player beats the computer.


Written in C# and built as WebGL.


##Refences

[Binary Search](https://en.wikipedia.org/wiki/Binary_search_algorithm)


[Dichotomic Search](https://en.wikipedia.org/wiki/Dichotomic_search)


## Sample Screenshot

![Image](https://jacobsalzberg.github.io/db/static/dicotomia.png)

"Maior" means "bigger", "Igual" means "equal" and "Menor" means "smaller".

## Link to the game

[Game](https://jacobsalzberg.github.io/Jogo-Dicotomia-UI/)

