# Menu Library for C++

A simple console-based menu handling library for C++.

## Overview

Author Faizan Moin

This library provides functionalities for creating interactive console menus in C++ programs. It includes functions for arrow key navigation, menu option highlighting, and user input handling.

## Features

- Arrow key control for menu navigation
- Menu option highlighting with customizable colors
- Interactive menu display for user selection

## Usage
1. Copy the menu.h file into cpp file directory
2. Include the "menu.h" header file in your C++ program.
3. Use the provided functions to handle menu interactions.

```cpp
#include <menu.h>
//or
#include "menu.h"


// Example usage
int main() {
    // Define menu options
    std::string menuOptions[] = {"Option 1", "Option 2", "Option 3"};

    // Display menu and get user selection
    int selectedOption = complete_menu(menuOptions, 3);

    // Perform actions based on the selected option
    // ...

    return 0;
}
```

## Compatibilty
- This library is designed for console-based applications.
- Ensure compatibility with the _getch() function and consider platform-specific differences.

## License

Feel free to customize this template to fit your preferences and provide more details about the library's functionalities, examples, and any additional information you think would be helpful for users.

