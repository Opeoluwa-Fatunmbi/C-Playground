# C++ Playground

A personal sandbox for learning and experimenting with C++, one small program at a time.

## Programs

| File | What it does |
| --- | --- |
| [`hello.cpp`](hello.cpp) | Reads two integers from the keyboard and prints their sum. |

## Getting started

### Prerequisites

You need a C++ compiler, such as one of these:

- **Windows:** [MinGW-w64](https://www.mingw-w64.org/) (g++) or Visual Studio (MSVC)
- **macOS:** Xcode Command Line Tools (`xcode-select --install`)
- **Linux:** g++ from your package manager (for example, `sudo apt install g++`)

### Build and run

```bash
g++ hello.cpp -o hello
./hello        # on Windows: hello.exe
```

### Example

```text
Enter a and b: 4 7
Sum: 11
```

## Project layout

```text
.
├── hello.cpp     # sum of two numbers
├── .gitignore    # keeps compiled binaries (*.exe, *.o) out of the repo
└── README.md
```

Compiled programs aren't committed. Build them locally with the commands above.

## Author

**Opeoluwa Fatunmbi** · [GitHub](https://github.com/Opeoluwa-Fatunmbi)
