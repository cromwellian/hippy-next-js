## Tip Calculator Webpage - Design Plan

**Files th be created:**

*   `tip-calculator.html`: This file will contain the HTML structure for the tip calculator form and display the results. It will include:
    *  Form elements for:
        *   Number of people
       *   Amount of bill
        *   Tip percentage
    *     JavaScript for calculations and dynamic updates.
    *   Basic CSS for styling.

**GitHub Repository:**

*   Repository Name: `hippy-next-js`
*   Owner: `cromwellian`

**GitHub Issues:**

**Core Features (Issues 1-3):**

*   **Issue 1: Create HTML form for input**
    *   Title: Design and implement HTML form for user input
    *   Body: Create the basic HTML structure for the tip calculator form. Include input fields for:
        *   Number of people (number input)
        *   Bill amount (number input)
        *   Tip percentage (number input or slider)
        Ensure proper labels and basic layout for the form elements.

*   **Issue 2: Implement JavaScript for calculation**
    *   Title: Implement JavaScript logic for tip calculation
    *   Body: Write JavaScript code to:
        *   Get values from the input fields.
        *   Calculate the tip amount based on the bill and tip percentage.
        *   Calculate the total bill amount (bill + tip).
        *   Calculate the amount each person should pay (total bill / number of people).

*   **Issue 3: Display calculated results on the page**
    *   Title: Display calculated tip and total per person
    *   Body: Modify the HTML to include designated areas to display the calculated results:
        *   Total tip amount
        *   Total bill amount
        *   Amount per person
        Use JavaScript to dynamically update these areas with the calculated values.

**Future Features & Improvements (Issues 4-8):**

*   **Issue 4: Feature - Add currency selection**
    *   Title: Implement Currency Selection
    *   Body: Add a dropdown or radio button to allow users to select their currency (e.g., USD, EUR, GBP). Update the display of the bill amount and per-person amount to reflect the selected currency.

*   **Issue 5: Feature - Allow splitting by item**
    *   Title: Implement Itemized Bill Splitting
    *   Body: Enhance the calculator to allow users to input individual items and their prices. Calculate tip and split based on the sum of items.

*   **Issue 6: Feature - Save tip preferences for future use (local storage)**
    *   Title: Implement Preference Saving using Local Storage
    *   Body: Use local storage to save user preferences like default tip percentage or currency. Load these preferences when the page is loaded for a better user experience.

*   **Issue 7: Feature - Add visual feedback/styling to the form**
    *   Title: Enhance UI with Visual Feedback and Styling
    *   Body: Improve the user interface with CSS styling to make the form more visually appealing and user-friendly. Add visual feedback for input validation and calculation results.

*   **Issue 8: Feature - Make the page responsive for mobile devices**
    *   Title: Make Page Responsive for Mobile Devices
    *   Body: Ensure the tip calculator webpage is responsive and works well on different screen sizes, especially mobile devices. Use CSS media queries to adjust layout and elements for optimal viewing on smaller screens.

**Issue Assignment:**

All issues are assigned to the username `cromwellian`.