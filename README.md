# CSC320 Module 1 Critical Thinking – Restaurant Info

A first Java program that prints a restaurant's name and address to the console.

## Overview

This repository holds Benjamin Mossberg's **CSU Global CSC320 (Programming I), Module 1 Critical Thinking Assignment, Option #2** (dated 18 MAR 2026 in `README.txt`). The program has no input and no logic beyond output: it shows the basic structure of a Java class, the `main` method, and `System.out.println`.

## Files

| File | Purpose |
|------|---------|
| `RestaurantInfo.java` | The program. The `RestaurantInfo` class has a single `main(String[] args)` method that calls `System.out.println` three times to print the restaurant's name, street address and city/state/ZIP. |
| `RestaurantInfo_Pseudocode.txt` | Pseudocode for the same program (`BEGIN`, three `DISPLAY` statements, `END`). |
| `RestaurantInfo.class` | A compiled copy of the program that was committed with the source. You can rebuild it with `javac`. |
| `README.txt` | The original assignment label and author/date line. |

## Build and run

Requires any JDK (8 or later).

```bash
javac RestaurantInfo.java
java RestaurantInfo
```

Output (verified):

```
Casa Bonita
6715 W Colfax Ave
Lakewood, CO 80214
```

## Concepts demonstrated

- Structure of a Java source file: a public class whose name matches the file name
- The `public static void main(String[] args)` entry point
- Console output with `System.out.println`
- Writing pseudocode before code
