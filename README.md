# get-next-line
(42 subject) the second 42 subject and one of the most useful ones for the beginning !

## Table of Content

* [Technologies](#technologies)
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [Utility](#utility)
* [Contributing](#contributing)

## Technologies

Project is created with:
* gcc 9.3.0

## Description

Very useful to do the simple task of parsing a file line by line.\
This version of get_next_line supports multiple fds, so you can open several files at the same times and read them simultaneously.

## Installation

Pull the project.\
\
Just compile the sources as shown below with your .c files and you can now use the function in your code !\
You also need to replace \[buffer_size\] with the number of bytes read per read() calls. 4096 is recommanded.\
Don't forget to #include "get_next_line.h" to your main otherwise it will not compile.

## Usage

````sh
gcc -Wall -Wextra -Werror -D BUFFER_SIZE=[buffer_size] <files>.c #compiles get-next-line srcs
````

## Utility

Useful in a lot of projects, a must have for any programmer !

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.