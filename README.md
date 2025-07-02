# school-management

A simple Java console application to manage teacher salaries and student fees.

## Installation & Run

### Clone the repository

```bash
$ git clone https://github.com/CandasKat/school-management.git
$ cd school-management
```

### Compile and execute

```bash
$ javac -d out src/ecole/manager/system/*.java
$ java -cp out ecole.manager.system.Main
```

## Project Structure

```bash
src/
└── ecole/manager/system/
    ├── Main.java       // Application entry point
    ├── Ecole.java      // Core school management logic (fees & salaries)
    ├── Teacher.java    // Teacher entity
    └── Student.java    // Student entity
```

## Features
- Add, update, and remove teachers

- Add, update, and remove students

- Record and track teacher salary payments

- Record and track student fee payments
