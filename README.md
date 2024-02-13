# Frontend Mentor - Launch countdown timer solution

This is a solution to the [Launch countdown timer challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/launch-countdown-timer-N0XkGfyz-).
This dynamic web application displays a countdown to a specific launch date set 14 days from the current date. Designed with HTML, CSS, and JavaScript, this app provides a visually appealing and interactive way to count down to an exciting event.

### Screenshot

(./design/desktop-preview.jpg)

### Links

- Live Site URL: (https://mariam-mantidze.github.io/Launch-countdown-timer/)

## Features

- **Dynamic Countdown**: Continuously updates to show the days, hours, minutes, and seconds remaining until the launch.
- **Responsive Design**: Looks great on a wide range of devices, from phones to desktops.
- **Visually Appealing**: Custom CSS for a modern and engaging user interface.

## How It Works

The application calculates the difference between the current date and time and a target date 14 days in the future. It breaks this difference down into days, hours, minutes, and seconds, displaying these in a countdown timer on the webpage.

### HTML Structure

The webpage is structured with separate containers for days, hours, minutes, and seconds, each displayed in its card for clarity and readability.

### CSS Styling

External CSS files apply styling to give the countdown timer a sleek look, including styles for the countdown cards, text, and background elements.

### JavaScript Functionality

The logic for calculating and updating the countdown timer is handled in JavaScript, using the `Date` object to get the current time and calculate the time until the target launch date. The countdown updates every second for a live countdown experience.

## Setup

1. **Clone the repository** to your local machine.
2. Open `index.html` in a web browser to view the countdown timer.

## Usage

The web application starts the countdown immediately upon loading. You can customize the target date in the JavaScript file to count down to any event of your choosing.

## Customization

Feel free to modify the HTML, CSS, and JavaScript files to suit your specific needs, whether for counting down to a product launch, special event, or personal milestone.

## Contributing

Contributions are welcome! Whether it's new features, design enhancements, or bug fixes, your input is valuable. Please submit issues or pull requests as you see fit.

Happy counting down to your next big event!
