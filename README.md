# Java Hello World Module Project

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A Java Hello World application built using the Java Platform Module System (JPMS), demonstrating modular project structure with Eclipse.

## Overview

This project showcases a minimal Java application organized as a named module (`ie.gmit.testmodule`). It illustrates how to set up a modular Java project with proper `module-info.java` declarations, package structure, and a main entry point. Originally created as an Eclipse-based project template for educational use.

## Features

- Java Platform Module System (JPMS) module declaration
- Named module: `ie.gmit.testmodule`
- Clean package structure (`ie.gmit.testpackage`)
- Javadoc-commented Main class
- Eclipse project configuration included

## Prerequisites

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) 9 or higher (module system required)
- [Eclipse IDE](https://www.eclipse.org/downloads/) (optional, project files included)

## Getting Started

### Installation

Clone the repository:

```bash
git clone https://github.com/danielcregg/java-hello-world-module-project.git
cd java-hello-world-module-project
```

### Usage

**Using the command line:**

```bash
javac -d out --module-source-path src $(find src -name "*.java")
java --module-path out -m ie.gmit.testmodule/ie.gmit.testpackage.Main
```

**Using Eclipse:**

1. Open Eclipse IDE
2. Import the project via **File > Import > General > Existing Projects into Workspace**
3. Select the cloned repository directory
4. Run `Main.java` as a Java Application

## Tech Stack

- **Language:** Java (9+)
- **Module:** `ie.gmit.testmodule`
- **IDE:** Eclipse (project files included)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
