# Box Animation on Selection

## Overview

This project demonstrates a simple and visually appealing box animation that occurs when a box is selected. The animation enhances the user experience and provides a clear indication of the selected box.

## Features

- **Box Animation:** Upon selecting a box, a smooth and engaging animation is triggered to highlight the selection.

- **Customizable:** Easily customize the animation duration, style, and other parameters to fit the design of your project.

- **Responsive:** The animation is designed to be responsive and work seamlessly across various screen sizes and devices.

## Getting Started

Follow these steps to integrate the box animation into your project:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/abdul-1432/Box-Animation-on-Selection
   ```

2. **Include the CSS and JS Files:**
   Add the `box-animation.css` and `box-animation.js` files to your project. Make sure to include them in your HTML file.

   ```HTML
   <link rel="stylesheet" href="path/to/box-animation.css">
   <script src="path/to/box-animation.js"></script>
   ```

3. **HTML Structure:**
   Create the HTML structure for your boxes. Each box should have a unique identifier.

   ```html
   <div class="box" id="box1"></div>
   <div class="box" id="box2"></div>
   <!-- Add more boxes as needed -->
   ```

4. **Initialize the Animation:**
   In your JavaScript file, initialize the box animation by calling the `initBoxAnimation` function.

   ```javascript
   document.addEventListener("DOMContentLoaded", function () {
       initBoxAnimation();
   });
   ```

5. **Customization (Optional):**
   Adjust the animation parameters in the `box-animation.css` file to match your project's design preferences.

## Example

Check out the [demo](https://codepen.io/seyedi/pen/MWZKRyd) to see the box animation in action.

## Contributing

If you'd like to contribute to this project, please follow the [contributing guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by [AwesomeAnimations](https://codepen.io/seyedi/pen/MWZKRyd).

---

Feel free to reach out if you have any questions or need further assistance!
