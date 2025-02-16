# 🧮 Calculator Application

**Video Demo:** [Watch on YouTube](https://youtu.be/WEFy49mCK2M)

This project is a **multi-functional calculator application** developed as a **CS50 final project** by **Buğra Han**. The application performs **basic arithmetic operations, advanced mathematical functions, and supports multiple number systems**. It is structured into three main categories based on complexity and features.

## 📌 Table of Contents

- [Simple Calculator Functionality](#simple-calculator-functionality)
- [Extended Calculator Functionality](#extended-calculator-functionality)
- [Calculator with Logic](#calculator-with-logic)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)

## ✨ Simple Calculator Functionality

This version includes:

- A numeric keypad layout similar to a traditional calculator.
- Real-time result display at the top of the screen.
- Support for sequential mathematical operations:
  - Pressing `=` displays the result.
  - Using an operator after `=` continues calculations with the previous result.
  - Entering a number after `=` starts a new calculation.
- Operations follow the order they are entered (e.g., `2 + 2 * 2 = 8`).
- Power (`^`) function available via the number button.

## 🏗️ Extended Calculator Functionality

This version enhances the basic calculator by adding:

- Improved UI with **graphic buttons** and color enhancements.
- **Number system conversions**: Convert results to **binary, octal, and hexadecimal** formats.
- **History Tracking**: View all calculations performed since app startup.

## 🔢 Calculator with Logic

The most advanced version includes:

- **Enhanced operation handling**: Calculates results only after pressing `=` (e.g., `2 + 2 * 2 = 6`).
- **Support for unlimited parameters**: Enables complex calculations.
- **Reverse Polish Notation (RPN) support**:
  - Uses a stack for systematic operator and operand processing.
  - Allows efficient handling of complex expressions.
  
**Example: RPN Calculation for `(3 + 4) * 2`**

1. Press `3`
2. Press `Enter`
3. Press `4`
4. Press `Enter`
5. Press `+`
6. Press `2`
7. Press `Enter`
8. Press `*`
9. Press `=` → Result: `14`

## 🔥 Features

- **Basic Operations**: Addition, subtraction, multiplication, and division.
- **Advanced Functions**: Power (`^`), conversions to **binary, octal, and hexadecimal**.
- **History Tracking**: Review all calculations in the session.
- **Responsive UI**: Adaptive layout for various screen sizes (phones & tablets).

## 🛠️ Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/hanbugra82/Calculator-.git
   ```
2. Ensure all dependencies are installed via `pom.xml`. Required dependencies:
   - [Maven Central Repository](https://central.sonatype.com/?smo=true)
   
   | Dependency            | Description                             |
   |----------------------|-----------------------------------------|
   | `JavaFX Controls`     | UI components for JavaFX applications  |
   | `exp4j`               | Mathematical expression parsing        |
   | `apfloat`             | Arbitrary precision arithmetic        |
   | `Apache Commons Math` | Advanced math functions               |
   | `JavaFX FXML`         | UI structure and XML-based components  |
   | `ControlsFX`          | Extended UI controls for JavaFX        |
   | `Ikonli`              | Icon library for JavaFX applications  |
   | `JUnit Jupiter API`   | Unit testing framework                |
   | `JUnit Jupiter Engine`| Execution engine for JUnit tests      |

3. **Install SceneBuilder**: [Download SceneBuilder](https://gluonhq.com/products/scene-builder/) to enable drag-and-drop UI design for JavaFX.

   - **Key Features:**
     - Drag-and-drop UI elements
     - FXML editing for custom UI modifications
     - Seamless integration with Java IDEs

## 📖 Usage

- Perform basic and advanced calculations.
- View and manage past calculations via **History Tracking**.
- Use **RPN mode** for efficient complex calculations.

## 📸 Screenshots

![Calculator Screenshot](src/main/resources/screenshots/screenshot.png)

---

🚀 **Enjoy seamless calculations with the CS50 Final Project Calculator!**

## Screenshots

![screenshot](src/main/resources/screenshots/screenshot.png)

