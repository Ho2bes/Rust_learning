# The Rust Programming Language - Learning Project

Welcome to my Rust learning project! This repository is a collection of examples, exercises, and projects that I am working on as I progress through [*The Rust Programming Language*](https://doc.rust-lang.org/book/), commonly known as "the Rust Book".

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Chapter Summaries](#chapter-summaries)
  - [Chapter 1: Getting Started](#chapter-1-getting-started)
  - [Chapter 2: Programming a Guessing Game](#chapter-2-programming-a-guessing-game)
  - [Chapter 3: Common Programming Concepts](#chapter-3-common-programming-concepts)
  - [Chapter 4: Understanding Ownership](#chapter-4-understanding-ownership)
  - [Chapter 5: Using Structs to Structure Related Data](#chapter-5-using-structs-to-structure-related-data)
  - [Chapter 6: Enums and Pattern Matching](#chapter-6-enums-and-pattern-matching)
  - [Chapter 7: Managing Growing Projects with Packages, Crates, and Modules](#chapter-7-managing-growing-projects-with-packages-crates-and-modules)
  - [Chapter 8: Common Collections](#chapter-8-common-collections)
  - [Chapter 9: Error Handling](#chapter-9-error-handling)
  - [Chapter 10: Generic Types, Traits, and Lifetimes](#chapter-10-generic-types-traits-and-lifetimes)
  - [Chapter 11: Writing Automated Tests](#chapter-11-writing-automated-tests)
  - [Chapter 12: An I/O Project: Building a Command Line Program](#chapter-12-an-io-project-building-a-command-line-program)
  - [Chapter 13: Functional Language Features: Iterators and Closures](#chapter-13-functional-language-features-iterators-and-closures)
  - [Chapter 14: More about Cargo and Crates.io](#chapter-14-more-about-cargo-and-cratesio)
  - [Chapter 15: Smart Pointers](#chapter-15-smart-pointers)
  - [Chapter 16: Fearless Concurrency](#chapter-16-fearless-concurrency)
  - [Chapter 17: Object-Oriented Programming Features of Rust](#chapter-17-object-oriented-programming-features-of-rust)
  - [Chapter 18: Patterns and Matching](#chapter-18-patterns-and-matching)
  - [Chapter 19: Advanced Features](#chapter-19-advanced-features)
  - [Chapter 20: Final Project: Building a Multithreaded Web Server](#chapter-20-final-project-building-a-multithreaded-web-server)
- [Contributing](#contributing)
- [Resources](#resources)
- [License](#license)

## Introduction

This project is my hands-on exploration of Rust, following the official book [*The Rust Programming Language*](https://doc.rust-lang.org/book/). The book provides a comprehensive guide to learning Rust, and this repository contains my implementations of the examples, exercises, and projects from each chapter.

## Project Structure

The repository is organized according to the chapters in the Rust Book.

## Getting Started

To get started with this project, you need to have Rust installed on your machine. If you haven't installed Rust yet, follow these instructions:

1. Install Rust using `rustup`:

    ```bash
    curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
    ```

2. Clone this repository:

    ```bash
    git clone https://github.com/your-username/rust-learning-project.git
    cd rust-learning-project
    ```

3. Navigate to the chapter you want to explore and run the examples or exercises:

    ```bash
    cd chapter_02_guessing_game/guessing_game
    cargo run
    ```

## Chapter Summaries

### Chapter 1: Getting Started
This chapter covers the initial setup and introduction to Rust. It includes instructions for installing Rust, creating a simple "Hello, World!" program, and an introduction to the `cargo` tool.

### Chapter 2: Programming a Guessing Game
In this chapter, we build a simple guessing game, which introduces basic concepts such as variables, loops, and user input.

### Chapter 3: Common Programming Concepts
This chapter dives into fundamental programming concepts like variables and mutability, data types, functions, comments, and control flow.

### Chapter 4: Understanding Ownership
Ownership is a unique feature of Rust that ensures memory safety without a garbage collector. This chapter explains ownership, borrowing, and lifetimes.

### Chapter 5: Using Structs to Structure Related Data
This chapter explores how to use structs to structure data, how to define methods on structs, and how to use the `dbg!` macro.

### Chapter 6: Enums and Pattern Matching
Here, we learn about enums, a powerful feature in Rust that allows you to define types that can represent multiple different kinds of values.

### Chapter 7: Managing Growing Projects with Packages, Crates, and Modules
This chapter covers how to organize and manage larger Rust projects using packages, crates, and modules.

### Chapter 8: Common Collections
In this chapter, we explore Rust’s standard collection types, including vectors, strings, and hash maps.

### Chapter 9: Error Handling
This chapter teaches how to handle errors in Rust using `Result` and `Option` types, and when to use `panic!`.

### Chapter 10: Generic Types, Traits, and Lifetimes
Generics, traits, and lifetimes are advanced Rust features that enable code reuse and ensure safety. This chapter explains these concepts in detail.

### Chapter 11: Writing Automated Tests
Automated tests are crucial for software reliability. This chapter covers how to write and run tests in Rust.

### Chapter 12: An I/O Project: Building a Command Line Program
This chapter walks through building a command-line tool in Rust, focusing on file input/output and command-line argument parsing.

### Chapter 13: Functional Language Features: Iterators and Closures
Rust has many features inspired by functional programming languages, such as iterators and closures. This chapter explores these features.

### Chapter 14: More about Cargo and Crates.io
This chapter dives deeper into using Cargo, including creating libraries and publishing to [crates.io](https://crates.io/).

### Chapter 15: Smart Pointers
Smart pointers are a key feature in Rust that enable ownership with more flexibility. This chapter covers `Box<T>`, `Rc<T>`, and `RefCell<T>`.

### Chapter 16: Fearless Concurrency
Concurrency is often difficult and error-prone, but Rust makes it safer. This chapter explores concurrency in Rust using threads and message passing.

### Chapter 17: Object-Oriented Programming Features of Rust
While Rust is not traditionally object-oriented, it does have some object-oriented features. This chapter discusses those features and how they differ from traditional OOP languages.

### Chapter 18: Patterns and Matching
Pattern matching in Rust is a powerful tool for controlling the flow of a program. This chapter covers how to use patterns in `match` expressions and other constructs.

### Chapter 19: Advanced Features
This chapter explores some of Rust’s more advanced features, including unsafe Rust, macros, and more.

### Chapter 20: Final Project: Building a Multithreaded Web Server
In this final chapter, we apply everything we've learned to build a simple multithreaded web server.

## Contributing

This is a personal learning project, but I welcome suggestions for improvement. Feel free to submit a pull request or open an issue if you have ideas for enhancing the project.

## Resources

- [*The Rust Programming Language*](https://doc.rust-lang.org/book/) - The official Rust book.
- [Rust Documentation](https://doc.rust-lang.org/) - The official Rust documentation.
- [Rust By Example](https://doc.rust-lang.org/rust-by-example/) - Learn Rust by solving examples.
- [crates.io](https://crates.io/) - The Rust community's package registry.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
