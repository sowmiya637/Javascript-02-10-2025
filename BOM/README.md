# Browser Object Model (BOM) Demo

## Project Overview
This is a simple interactive demo to showcase **Browser Object Model (BOM)** features using JavaScript.  
Users can interact with different buttons to see various browser-related information and dialogs.

The demo uses:

- Alert, Confirm, Prompt dialogs  
- Window location info  
- Navigator info  
- Screen info  

All data is dynamically displayed on the page.

---

## Features

### 1. Show Alert
- Displays a popup message using `alert()`.

### 2. Show Confirm
- Displays an OK/Cancel dialog using `confirm()`.  
- Shows the result in the page (`You are 18+` or `You are under 18`).

### 3. Show Prompt
- Prompts the user to enter their name using `prompt()`.  
- Displays a personalized greeting on the page.

### 4. Show Location
- Displays the current URL information:  
  - Full URL (`location.href`)  
  - Host (`location.host`)  
  - Pathname (`location.pathname`)

### 5. Show Navigator
- Displays browser and platform information using the `navigator` object:  
  - Browser name (`navigator.appName`)  
  - User agent (`navigator.userAgent`)  
  - Platform (`navigator.platform`)  
  - Language (`navigator.language`)

### 6. Show Screen Info
- Displays screen size and available screen size using the `screen` object:  
  - Width, Height  
  - Available Width, Available Height
