# Large-Number-Calculator
A large number calculator that can perform calculations on numbers with digits up to several thousand.
### Key Features:

1. **HTML Structure**:
   - The webpage is structured with a `div` element for the calculator that contains an input for the display and buttons for input and operations.

2. **CSS Styling**:
   - The design has a modern feel with rounded corners, shadows, and smooth transitions.
   - The background is a gradient, and the layout is centered both vertically and horizontally using Flexbox.
   - Buttons have hover and active effects, making them interactive and visually appealing.

3. **Google Fonts**:
   - The Roboto font is loaded from Google Fonts for a clean and modern text appearance.

4. **JavaScript Functionality**:
   - `appendToDisplay(value)`: Adds the clicked button value to the display.
   - `clearDisplay()`: Clears the input field.
   - `calculateResult()`: Evaluates the expression entered in the display, converting percentages and exponentiation symbols (`^`), and using `BigInt` for large number calculations.

5. **Big Number Support**:
   - The calculator can handle large numbers by converting numeric expressions into `BigInt` format, which allows for operations on integers larger than the normal JavaScript number type.

6. **Interactive Buttons**:
   - Special functions include clear (`C`), exponentiation (`^`), percentage (`%`), and calculation (`=`). The design distinguishes the special buttons visually with different colors.

In summary, this code creates a simple but visually modern calculator with support for large number calculations using `BigInt`, smooth animations, and basic mathematical operations.
