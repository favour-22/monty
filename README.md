#MONTY

`monty` is an interpreter of Monty ByteCodes files which is a scripting language just like Python.

## About the Monty language

This is a language that contains specific instructions to manipulate data information (stacks or queues), where each instruction (*called opcode*) is sended per line. Files which contains Monty byte codes usually have the `.m` extension.





## Technologies

* Interpreter was written with C language
* C files are compiled using `gcc`
* C files are written according to the betty coding standard
* Tested on Ubuntu 20.04 LTS

## Usage

To compile all files:
```bash
$ gcc -Wall -Werror -Wextra -pedantic *.c -o monty

$
```

The **synopsis** of the interpreter is the following:
```bash
$ ./monty [filename]
$
```


