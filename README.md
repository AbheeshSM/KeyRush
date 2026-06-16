# KeyRush - Typing Speed Test

KeyRush is a simple and interactive typing speed test application built using **HTML**, **CSS**, and **JavaScript**. It allows users to practice typing with randomly selected quotes while tracking their performance through real-time statistics.

## Features

* Random typing passages generated from a predefined quote collection
* Real-time character validation
* Highlights:

  * Correctly typed characters
  * Incorrectly typed characters
  * Current cursor position
* Calculates:

  * Words Per Minute (WPM)
  * Accuracy Percentage
  * Time Taken
* Restart and retake tests instantly
* Clean and responsive user interface
* Automatic scrolling while typing long passages

## Technologies Used

* HTML5
* CSS3
* Vanilla JavaScript

## Project Structure

```
TypeRow/
│
├── index.html      # Main application structure
├── index.css       # Styling and UI design
├── app.js          # Typing logic and statistics calculation
└── README.md
```

## How It Works

1. Click the **Start** button.
2. A random quote is displayed.
3. Begin typing the displayed text.
4. Characters are checked in real time:

   * Correct characters are highlighted.
   * Incorrect characters are marked in red.
5. When the quote is completed:

   * Timer stops automatically.
   * WPM is calculated.
   * Accuracy percentage is displayed.
