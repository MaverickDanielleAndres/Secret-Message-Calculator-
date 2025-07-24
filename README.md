
# Secret Message Calculator 💖

This is a fun, interactive calculator built with HTML, CSS, and JavaScript. It looks and functions like a standard calculator, but with a special twist! When you solve a specific hidden equation (`23 * 9 - 150 + 6 - 20`), it reveals a surprise love message in a beautiful modal popup.

It's perfect for:

*   **Surprising someone special:** Hide a personal message for them to discover.
*   **Long Distance Relationship (LDR) projects:** A creative way to send a digital love note.
*   **Fun experiments:** A playful twist on a classic web element.

## Features

*   **Fully Functional Calculator:** Handles basic arithmetic operations (addition, subtraction, multiplication, division).
*   **Responsive Design:** Looks good on both desktop and mobile devices.
*   **Special Surprise Trigger:** Solving the secret equation (`23 * 9 - 150 + 6 - 20`) unlocks a hidden message.
*   **Animated Message Display:** The calculation result and the surprise message are displayed with a typewriter effect.
*   **Elegant Modal Popup:** The secret message appears in an animated modal with floating hearts.
*   **Keyboard Support:** You can use your keyboard (numbers, operators, Enter, Backspace, C/Escape) to interact with the calculator.

## How to Edit the Code

Want to customize the surprise message or change the secret equation? It's easy!

1.  **Open the HTML File:** Open the `index.html` file (or whatever you've named it) in a text editor (like VS Code, Sublime Text, Notepad++, or even Notepad).
2.  **Find the Modal Content:**
    *   Scroll down to the section containing the modal.
    *   Look for `<div class="love-letter">`.
    *   Inside this div, you'll find the `<h1 class="love-title">` and several `<p class="love-message">` tags. These contain the text that appears in the surprise popup.
    *   **Edit the text** within these tags to write your own personalized message. You can add or remove `<p>` tags as needed.
3.  **Change the Secret Equation (Optional):**
    *   Find the `<script>` section (usually towards the bottom of the file).
    *   Look for the `calculate()` function.
    *   Inside this function, you'll see a line: `if (expression === '23*9-150+6-20') {`.
    *   **Change the string `'23*9-150+6-20'`** to the desired mathematical expression you want users to solve. Make sure to write it using standard JavaScript operators (`*` for multiplication, `/` for division). For example, to use `10 + 5 * 2`, you would change it to `if (expression === '10+5*2') {`.
    *   *(Advanced Tip: You could also modify the logic to check for a range of results or use more complex conditions).*

That's it! Save the file and open it in your web browser to see your changes.

## Usage

1.  Save the provided HTML code as an `.html` file (e.g., `calculator.html`).
2.  Open the file in a web browser.
3.  Use the calculator normally or try solving the secret equation: `23 * 9 - 150 + 6 - 20`.
4.  Upon solving the secret equation correctly, watch the display and enjoy the surprise modal!

Enjoy this little project and have fun customizing it!
