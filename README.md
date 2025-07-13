# Sign Up Page - Little Lemon

This repository contains the `signup.html` file, which is the sign-up page for the Little Lemon project.

## Table of Contents

- [Features](#features)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Styling](#styling)
- [Copyright](#copyright)

## Features

* **User Registration:** Allows users to create an account by providing their first name, last name, email, and password.
* **Form Validation:** Includes basic HTML5 form validation for required fields and minimum lengths for first name and password.
* **Password Confirmation:** Provides a field to confirm the entered password.
* **Basic Styling:** Incorporates a simple CSS rule to visually indicate invalid input fields.

## File Structure

## Usage

To view the sign-up page:

1.  Clone this repository or download the `signup.html` file.
2.  Open the `signup.html` file in your web browser.

The page will display a form where users can input their details to sign up.

## Styling

The page includes embedded CSS within the `<style>` tags in the `<body>` section.

* **Invalid Input Highlight:** Input fields with invalid data (e.g., `minlength` not met for first name or password) will have a 2px solid red border. This is achieved using the `:invalid` pseudo-class selector.

    ```css
    input:invalid {
        border: 2px solid red;
    }
    ```

    *Note: There is a typo in the provided CSS (`input :invalid`). It should be `input:invalid` for the pseudo-class to apply directly to the input element.*

## Copyright

© Copyright by Little Lemon. All rights reserved.
