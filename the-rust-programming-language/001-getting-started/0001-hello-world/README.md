# Important Details about Rust Code

When writing Rust code, it's essential to pay attention to the following important details:

## 1. Indentation Style

Rust follows a style convention of using four spaces for indentation, not tabs. Ensure that your code is consistently indented with four spaces for better code readability and adherence to Rust's style guidelines.

## 2. Macros vs. Functions

In Rust, the `println!` statement calls a Rust macro, not a function. It's important to note that when you see a `!` after a function-like name, you are invoking a macro. Macros in Rust have their own rules and behavior, which can differ from regular functions. We will delve deeper into Rust macros in Chapter 19.

## 3. String Argument in println!

In the code example, you'll notice the string "Hello, world!" being passed as an argument to `println!`. This string is printed to the screen when the program is executed. You can customize this string to display different messages.

## 4. Semicolons (;) to End Statements

In Rust, it is customary to end most lines of code with a semicolon (`;`). The semicolon indicates the end of an expression and is a crucial part of Rust's syntax. It signifies that the current expression is complete, and the next one can begin.

Remember these details while writing Rust code to ensure consistent style, proper use of macros, string handling, and statement termination.

Now, you're equipped with some fundamental insights for writing Rust code effectively.

# Running a Rust Program

This section provides instructions for compiling and running a Rust program on Linux, macOS, and Windows systems.

## Prerequisites

Before running a Rust program, ensure that you have:

- Installed Rust using the installation instructions provided earlier in this README.
- Created or obtained a Rust source code file (e.g., `main.rs`) that you want to compile and run.

## Compilation and Execution (Linux/macOS)

To compile and run a Rust program on Linux or macOS, follow these steps:

1. **Open Your Terminal**

   Open your terminal on your Linux or macOS system.

2. **Navigate to the Directory**

   Use the `cd` command to navigate to the directory where your Rust source code file (`main.rs`) is located.

   ```shell
   $ cd path/to/your/rust/project
   ```

3. **Compile the Rust Program**
   Compile the Rust program with the following command:

   ```shell
   $ rustc main.rs
   ```

4. **Run the Compiled Program**
   After a successful compilation, run the compiled program using:

   ```shell
   $ ./main
   ```

   You should see the output, for example:

   ```
   Hello, world!
   ```

## Compilation and Execution (Windows)

To compile and run a Rust program on Windows, follow these steps:

1. **Open Your Command Prompt or PowerShell**

   Open your command prompt or PowerShell on your Windows system.

2. **Navigate to the Directory**

   Use the `cd` command to navigate to the directory where your Rust source code file (`main.rs`) is located.

   ```shell
   $ cd path/to/your/rust/project
   ```

3. **Compile the Rust Program**
   Compile the Rust program with the following command:

   ```shell
   $ rustc main.rs
   ```

4. **Run the Compiled Program**
   After a successful compilation, run the compiled program using:

   ```shell
   $ .\main.exe
   ```

   You should see the output, for example:

   ```
   Hello, world!
   ```
