# Shopping App

This project is a simple Flutter-based shopping application interface that includes a **Sign-Up Page** and a **Shopping Screen**. The app validates user inputs and provides feedback through dialogs and snack bars. Below are the project details.

## Problem Statement:
Title: Create signup page to access the shopping screen


## Features

### 1. **Sign-Up Page**
- **Full Name Field**:
  - Validates that the first letter is capitalized.
  - Displays a snack bar with an error message if validation fails.
- **Email Field**:
  - Validates that the input contains `@`.
  - Displays a snack bar with an error message if validation fails.
- **Password Field**:
  - Validates that the password has at least 6 characters.
  - Displays a snack bar with an error message if validation fails.
- **Confirm Password Field**:
  - Validates that it matches the password field.
  - Displays a snack bar with an error message if validation fails.
- **Sign-Up Button**:
  - Shows a dialog with the message "Account created successfully" if all fields are validated.
  - Navigates to the Shopping Screen when the **Close** button in the dialog is clicked.

### 2. **Shopping Screen**
- Displays two sections:
  - **Product Grid**: Displays a grid of products.
  - **Hot Offers**: Displays a horizontal list of special offers.
- Each product has an **Add to Cart** button that shows a snack bar message: "Your item added to the cart✨".


### 3. **Animate between the signup page and shopping page**

- When the user clicks Close in the success dialog:
  - The dialog fades out smoothly.
  - The Shopping Screen fades in with a smooth transition.
  - This enhances the user experience by providing a visually appealing transition instead of an abrupt page switch.
    
## Demo
https://github.com/user-attachments/assets/976b4d04-5d22-4655-b944-f15c1223b7dd
