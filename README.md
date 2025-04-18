# grish(a) - A Custom UNIX Shell

> A Tribute to AoT.

**grish(a)** is a custom-made, AoT-themed Unix shell written in **C**, designed for fun, personal learning, and a bit of flair. It supports:

- Bash-like commands
- Built-in commands like `cd`, `exit`, and more
- Custom AoT-themed commands like `eren`, `yeager`, `shifter`, `titan`, `paradis`
- Two extra special commands - `rumbling` and `scouts`. No spoilers, have fun using them ;) 


## Project Structure

```bash
grisha-shell/
├── src/
│   ├── main.c              
│   ├── shell.c             
│   ├── parser.c            
│   ├── executor.c          
│   ├── builtins.c          
│   ├── utils.c             
├── include/
│   ├── shell.h
│   ├── parser.h
│   ├── executor.h
│   ├── builtins.h
│   ├── utils.h
├── Makefile
├── README.md
├── .gitignore
└── LICENSE
```

**Note:** since this shell uses Unix-specific headers, it will likely not run on Windows. I haven't tested it on Windows or macOS.

## Build Instructions

    # in cwd, production
    make
    # or debug
    make debug

## Run

    ./grisha

