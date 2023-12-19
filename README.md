# Calculator
Android app based calculator using Java language

Introduction

Welcome to the Calculator App, a simple yet powerful calculator designed and implemented using Android Studio and Java. This application serves as a versatile tool for performing basic arithmetic operations, making mathematical calculations a breeze on your Android device. Whether you're a student, professional, or anyone in need of quick and accurate calculations, this app has got you covered.

Features

1. User-Friendly Interface
The Calculator App boasts an intuitive and user-friendly interface that ensures a seamless user experience. The design prioritizes simplicity, allowing users to easily navigate through the app and perform calculations without any hassle. The layout is clean, and the buttons are logically arranged, making it accessible for users of all levels of expertise.

2. Basic Arithmetic Operations
Performing fundamental arithmetic operations is the core functionality of this calculator. Addition, subtraction, multiplication, and division are all supported, ensuring that users can handle a wide range of mathematical tasks with ease. The app also includes a clear display that shows the input and output, making it simple to track and verify calculations.


About the app:

1. Variables and Initialization
The `MainActivity` class extends `AppCompatActivity` and includes variables for the first number (`firstNum`) and the current operation (`operation`). These variables are crucial for storing the user's input and the selected arithmetic operation.
2. User Interface Setup
In the `onCreate` method, the layout is set using `setContentView(R.layout.activity_main)`. Buttons and TextView are initialized by finding their respective views in the XML layout using `findViewById`.

3. Button Click Listeners

  Numeric Buttons
A loop is used to set click listeners for numeric buttons (0-9). When a numeric button is clicked, the app appends the button's value to the displayed screen, allowing users to input multi-digit numbers.

  Operator Buttons
Similar to numeric buttons, operators (+, -, *, /) have click listeners. When an operator is clicked, the app captures the current number on the screen as the `firstNum` and stores the selected operation. The screen is then reset to "0" to input the next number.

  Other Buttons
- AC (All Clear): Resets the `firstNum` and sets the screen to "0".
- DEL (Delete): Removes the last character from the screen.
- . (Decimal Point): Adds a decimal point to the screen if not already present.

  ON/OFF Buttons
- ON: Makes the screen visible and sets it to "0".
- OFF: Hides the screen.

  Equal Button
When the equal button is clicked, the app performs the operation based on the stored operator and displays the result on the screen. The `firstNum` is updated with the result for further calculations.

4. XML Layout
The XML layout (`activity.xml`) is designed using a RelativeLayout to position the screen and buttons. LinearLayouts are used to group buttons logically, making the layout organized and easy to read.

5. Styling
Buttons are styled using a `Button1` style for operators and a `Button2` style for numeric and special buttons. The screen (`TextView`) is styled with bold text, a larger font size, and white text color.

I hope you find the Calculator App helpful in your daily tasks.

7. Functionality
The app handles basic arithmetic operations, including addition, subtraction, multiplication, and division. It also includes features like clearing the screen, deleting the last input, and turning the calculator on/off.

The use of loops and ArrayLists minimizes redundancy in code, making it more maintainable. The app provides a straightforward and functional calculator interface for users.
