# Local Storage Form

## Overview

This is a simple web project that demonstrates how to store user input data in the browser using **Local Storage**. 
The form collects basic user information and saves it locally so it can persist even after the browser is refreshed or closed.

## Features

* HTML form with fields for:

  * Username
  * Email
  * Phone number
* Stores form data in **browser localStorage**
* Uses JavaScript to handle form submission
* Prevents page reload using `event.preventDefault()`

## Technologies Used

* HTML
* JavaScript
* Browser Local Storage API

## How It Works

1. The user enters their **username, email, and phone number**.
2. When the **Submit** button is clicked:

   * JavaScript captures the form data.
   * The data is stored in **localStorage** with keys:

     * `username`
     * `email`
     * `phone`
3. The stored data can be viewed in the browser's **Developer Tools → Application → Local Storage**.

## Project Structure

```
local-storage-form
│
├── index.html
├── index.js
└── README.md
```

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/local-storage-form.git
```

2. Open the project folder.

3. Open `index.html` in your browser.

## Learning Outcome

This project helps understand:

* DOM event handling
* Form submission handling
* Using `localStorage` to store data in the browser
* Basic JavaScript interaction with HTML forms
