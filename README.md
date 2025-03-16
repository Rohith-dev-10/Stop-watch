# Stopwatch

A simple, elegant stopwatch application with start, stop, and reset functionality. This stopwatch displays time in hours, minutes, seconds, and milliseconds format.

> **Note:** This project was made in the learning stage for practice purposes.

## Features

- Precise timing with millisecond accuracy
- Clean, minimalist user interface
- Three control buttons:
  - Start: Begin or resume the stopwatch
  - Stop: Pause the stopwatch
  - Reset: Return the stopwatch to 00:00:00:00
- Responsive design with hover effects

## Project Structure

- `index.html` - Contains the basic structure and elements
- `index.css` - Styling for the stopwatch and buttons
- `index.js` - JavaScript logic for timing functionality

## How It Works

The stopwatch uses JavaScript's `Date.now()` method to calculate elapsed time with millisecond precision. The timer updates every millisecond using `setInterval()`. Times are formatted to always display two digits for each time unit.

## Usage

Simply open the `index.html` file in any modern web browser to use the stopwatch:

```
$ open index.html
```

## Learning Outcomes

This project demonstrates:
- Working with time measurements in JavaScript
- DOM manipulation
- Event handling
- CSS styling techniques including flexbox and transitions
- Time formatting and display

## Customization

You can easily customize:
- Colors by modifying the HSL values in the CSS file
- Button sizes and shapes
- Display font and styling

## License

[MIT](https://choosealicense.com/licenses/mit/)
