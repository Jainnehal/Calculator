# Calculator
# Calculator Project

This project is a simple calculator application built using Java Swing. It supports both standard and scientific calculator functionalities, along with customizable themes.

## Features

- **Standard Calculator**: Basic arithmetic operations (addition, subtraction, multiplication, division, and modulus).
- **Scientific Calculator**: Advanced operations (square root, power, and logarithm).
- **Customizable Themes**: Switch between different themes to change the calculator's appearance.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher

### Installing

1. Clone the repository to your local machine:

    ```sh
    git clone https://github.com/Jainnehal/Calculator.git
    ```

2. Navigate to the project directory:

    ```sh
    cd Calculator
    ```

3. Compile the Java source files:

    ```sh
    javac -d bin src/com/houarizegai/calculator/ui/CalculatorUI.java
    ```

4. Run the application:

    ```sh
    java -cp bin com.houarizegai.calculator.ui.CalculatorUI
    ```

## Usage

- **Standard Mode**: Perform basic arithmetic operations. Select "Standard" from the calculator type dropdown.
- **Scientific Mode**: Access advanced operations like square root, power, and logarithm. Select "Scientific" from the calculator type dropdown.
- **Themes**: Change the appearance by selecting different themes from the theme dropdown.

## Project Structure

- `src/com/houarizegai/calculator/ui/CalculatorUI.java`: The main class that creates and manages the calculator's user interface.
- `src/com/houarizegai/calculator/theme/ThemeLoader.java`: Utility class for loading themes.
- `src/com/houarizegai/calculator/theme/properties/Theme.java`: Represents a theme with various color properties.
- `src/com/houarizegai/calculator/util/ColorUtil.java`: Utility class for color conversion.

## Authors

- **Nehal Jain**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the simplicity and functionality of basic calculators.
