# Fillit
### 42 - Project #2

### From the PDF
Fillit is a project that lets you discover and familiarize yourself with a recurring problematic in programming: searching for the optimal solution among a huge set of possibilities. 

In this particular project, you will be in charge of creating an algorithm which fits some Tetriminos together into the smallest possible square.
A Tetriminos is a 4-blocks geometric figure that most of you might knows thanks to the popular game Tetris.

The program takes a file as a parameter which contains a list of Tetriminos which must be arranged to create the smallest square possible. Obviously, your main goal is to find this smallest square in the minimal amount of time, despite a exponentially growing number of possibilities each time a piece is added.

For the complete instructions, check out [fillit.en.pdf]

### Usage

Build the executable and run it with the tetriminos' file as a parameter

	make
	./fillit /path/to/file

Example:

	./fillit samples/sample

[fillit.en.pdf]: https://github.com/erredavila/fillit/blob/master/fillit.en.pdf
