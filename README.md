# ValuePigeon - A C++ Program for Item Valuation (Simplified Example)

This is a simplified C++ program to demonstrate calculating the total value of a set of items. It focuses on basic calculations and output and does not include more advanced features like user input or data storage.

## Features

* **Calculate Total Value:** Calculates the total value of a set of items based on the number of items and the cost per item.
* **Display Results:** Displays the number of items, cost per item, and the calculated total value.

## Building and Running

1. **Prerequisites:**
    * A C++ compiler (e.g., g++, clang)

2. **Compilation:**
    ```bash
    g++ -o valuepigeon main.cpp
    ```

3. **Execution:**
    ```bash
    ./valuepigeon
    ```

## Usage

The program will run and immediately display the hardcoded item information and the calculated total cost to the console.

## Code Structure

* `main.cpp`: Contains the main program logic, including variable declarations and output statements.

## Example `main.cpp` (The Code You Provided):

```cpp
#include <iostream>
using namespace std;

int main () {
    // Create variables of different data types
    int items = 50;
    double cost_per_item = 9.99;
    double total_cost = items * cost_per_item;
   string currency = 'GLB';

    // Print variables
    cout << "Number of items: " << items << "\n";
    cout << "Cost per item: " << cost_per_item << "" << currency << "\n";
    cout << "Total cost = " << total_cost << "" << currency << "\n"; 
    return 0;
}
