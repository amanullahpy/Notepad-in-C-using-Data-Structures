# Notepad in C++ Using Data Structures

A console-based Notepad project developed in C++ as part of a university Data Structures course. The project explores how fundamental data structures and algorithms can support text-related functionality, including Huffman encoding and automatic word suggestions.

## Overview

This project demonstrates the practical application of data structures in a simple Notepad-style program. It includes separate C++ source files for Huffman encoding and word suggestions, along with a dictionary file containing commonly used words.

The primary objective is to understand how data structures can be applied to text processing, encoding, and word prediction.

## Features

- **Huffman Encoding:** Includes a C++ implementation of Huffman encoding for exploring text compression concepts.
- **Word Suggestions:** Provides a word-suggestion component intended to suggest words as users type.
- **Dictionary-Based Suggestions:** Uses `dictionary.txt` as a source of commonly used words.
- **Data Structures in Practice:** Demonstrates the use of data structures to solve practical programming problems.
- **Modular Source Files:** Separates the encoding and word-suggestion implementations into different source files.

The exact user interface and available text-editing operations depend on the current source code.

## Technology Stack

| Technology | Purpose |
|---|---|
| C++ | Core implementation |
| Data Structures | Organizing and processing text-related data |
| Huffman Coding | Encoding and compression concepts |
| Dictionary File | Providing words for suggestions |
| Standard C++ Libraries | General-purpose programming utilities |

## Repository Structure

```text
Notepad-in-C-using-Data-Structures/
├── Source.cpp
├── huffman.cpp
├── dictionary.txt
├── DSA 1.docx
└── README.md
```

- `Source.cpp` — Contains the main source for the word-suggestion functionality, according to the original project description.
- `huffman.cpp` — Contains the Huffman encoding implementation.
- `dictionary.txt` — Contains words used by the suggestion component.
- `DSA 1.docx` — Supporting project document.
- `README.md` — Project documentation.

## Getting Started

### Prerequisites

Install a C++ compiler, such as:

- GCC or G++
- MinGW-w64 on Windows
- Clang on supported platforms

You can use Visual Studio Code, Visual Studio, Code::Blocks, or another C++ IDE.

### 1. Clone the Repository

```bash
git clone https://github.com/amanullahpy/Notepad-in-C-using-Data-Structures.git
cd Notepad-in-C-using-Data-Structures
```

### 2. Compile the Word-Suggestion Program

If `Source.cpp` contains its own `main()` function and can be compiled independently, run:

```bash
g++ Source.cpp -o notepad
```

On Windows:

```bash
notepad.exe
```

On Linux or macOS:

```bash
./notepad
```

Keep `dictionary.txt` in the working directory if the program loads it using a relative file path.

### 3. Compile the Huffman Encoding Program

If `huffman.cpp` is a standalone program with its own `main()` function, compile it separately:

```bash
g++ huffman.cpp -o huffman
```

On Windows:

```bash
huffman.exe
```

On Linux or macOS:

```bash
./huffman
```

These commands assume that each source file is independently compilable. If the files share functions or classes, compile and link them together according to their actual dependencies.

## How It Works

### 1. Word Suggestions

The suggestion component uses `dictionary.txt` as a word source. Its purpose is to retrieve or recommend relevant words based on user input.

The exact matching strategy, data structure, and behavior should be verified in `Source.cpp`.

### 2. Huffman Encoding

Huffman coding is a lossless compression technique that assigns variable-length binary codes to symbols based on their frequencies. Frequently occurring symbols generally receive shorter codes, while less frequent symbols receive longer codes.

The `huffman.cpp` file contains the project's implementation of this concept. The actual input format, output format, and supported decoding behavior depend on the code.

## Learning Objectives

This project provides an opportunity to explore:

- Practical applications of data structures.
- Text processing and dictionary-based word retrieval.
- Huffman coding and lossless compression.
- Modular C++ program organization.
- File handling and reading text resources.
- Compilation and execution of C++ programs.

## Future Improvements

Potential enhancements include:

- Integrating the word-suggestion and Huffman components into one consistent application.
- Adding text-file loading and saving.
- Implementing more efficient dictionary lookup.
- Supporting multiple word suggestions ranked by relevance.
- Adding input validation and error handling.
- Providing tests for word matching and Huffman encoding and decoding.
- Documenting the data structures used and their time complexity.
- Adding screenshots or a demonstration of the application.

These are possible extensions rather than claims about existing functionality.

## Academic Context

This project was developed collaboratively as part of a university Data Structures course. It focuses on applying data structures and algorithms to a Notepad-style programming project.

## Author

**Aman Ullah and project collaborators**

GitHub: [@amanullahpy](https://github.com/amanullahpy)

## License

No license is specified in this README. Add a `LICENSE` file if you intend to permit others to reuse, modify, or distribute the project.

---

For educational use, review the source files to understand how each data structure and algorithm contributes to the application's behavior.
