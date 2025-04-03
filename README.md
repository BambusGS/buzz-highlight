# Buzz Syntax Highlighting for VS Code

A surprisingly comprehensive syntax highlighting extension for the Buzz programming language (.bzz files) created at 3 AM.

## About

This extension was created by a WPI student during one of those long, exhausting nights of coding. Despite being tired, confused, and ready to collapse, I managed to put together this syntax highlighter to make working with Buzz code a bit more bearable.

The Buzz language itself was developed by Carlo Pinciroli at Worcester Polytechnic Institute (WPI) and is available at [https://github.com/buzz-lang](https://github.com/buzz-lang).

## Features

- Syntax highlighting for .bzz files
- Supports all Buzz language keywords, operators, and built-in functions
- Highlights all the robot swarm programming constructs that make Buzz unique
- Makes your code look prettier when you're debugging at 3 AM
- Highlights every namespace and function that was documented at the time of creation (which is way more than I planned)

## Installation

1. Download the extension
2. In VS Code, go to Extensions (Ctrl+Shift+X)
3. Click on the "..." at the top of the Extensions panel
4. Select "Install from VSIX..."
5. Choose the downloaded extension file
6. Enjoy syntax highlighting (and maybe get some sleep)

## Usage

The extension automatically activates when you open a .bzz file in VS Code.

## Supported Syntax

- **Keywords**: var, function, if, elseif, else, while, for, foreach, include, return, in, exec, not, and, or
- **Storage Types**: nil, integer, float, string, table, closure, userdata
- **Namespaces**: math, string, io, swarm, stigmergy, neighbors, queue
- **Special Variables**: self, id, errno, error_message
- **Built-in Functions**: 
  - Core: type, size, foreach, map, reduce, log, print
  - Math: abs, log, exp, sqrt, sin, cos, tan, min, max, and more
  - Swarm operations: join, select, leave, in, exec
  - Stigmergy: create, get, put, size
  - Robot neighbors: broadcast, listen, ignore

Honestly, there's way more highlighting than I expected to implement, but insomnia is a powerful motivator.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Created with bloodshot eyes by:
BambusGS (Jakub Jandus) - [GitHub](https://github.com/BambusGS/buzz-highlight.git)

## Acknowledgements

- Carlo Pinciroli for creating the Buzz language in the first place
- Caffeine for making this project possible
- My pillow for patiently waiting for me all night

---

*Note: This extension was created by a sleep-deprived student. If you find any issues, they were definitely caused by the lack of will to do anything.*

*Disclaimer: Parts of this code were actually written with the help of AI. If something is wrong, I'm blaming the algorithms, not my sleep-deprived brain. Although it's probably both.*
