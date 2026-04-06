# DesafioControleFluxo (Flow Control Challenge)

## Overview
This project was created as part of a Java learning exercise focused on **flow control, loops, and exception handling**.  
The program receives two integer parameters from the terminal and prints a sequence of numbers based on the difference between them.  
If the first parameter is greater than the second, a custom exception (`ParametrosInvalidosException`) is thrown.

---

## Project Structure
DesafioControleFluxo/
│
├── src/
│   └── main/
│       └── java/
│           └── br/
│               └── com/
│                   └── desafio/
│                       ├── Contador.java
│                       └── ParametrosInvalidosException.java
│
├── .vscode/
│   ├── launch.json
│   └── settings.json
│
├── bin/
│
└── README.md

Code

---

## How It Works
- The program asks the user for two integer inputs.
- If the **first number is greater than the second**, it throws a `ParametrosInvalidosException` with the message:
The second parameter must be greater than the first

Code
- Otherwise, it calculates the difference and prints:
Printing number 1
Printing number 2
...
Printing number N

Code

---

## Example
Input:
First parameter: 12
Second parameter: 30

Code

Output:
Printing number 1
Printing number 2
...
Printing number 18

Code

---

## How to Compile and Run (Linux)
1. Navigate to the project folder:
   ```bash
   cd DesafioControleFluxo
Compile the Java files:

bash
javac -d bin src/main/java/br/com/desafio/*.java
Run the program:

bash
java -cp bin br.com.desafio.Contador
Requirements
Java JDK 8 or higher

Any IDE (Visual Studio Code, Eclipse, IntelliJ) or terminal

Author
Project developed by Jamersom as part of a Java learning challenge.
