# Sehar's PlayArea created using JavaScript

This is an interactive web page where you can:
1. Replace the text in the heading with your name.
2. Move two animated boxes within a container.
3. Change the background color of the container.

## Features

### 1. Replace 'My' Play Area with 'Your' Play Area
- Enter your name in the text input field.
- Click the **Submit** button.
- The heading will update, replacing `'My'` Play Area with `'Your'` Play Area, capitalizing the first letter of your name.

### 2. Move the Boxes
- Click the **Click Here** button to start moving two animated boxes inside a container.
- The boxes will move diagonally within the container. The movement path is controlled with JavaScript.

### 3. Change the Background Color
- Use the color picker to choose a color.
- The background color of the container will change to the selected color.
- Click the **Change Background Color** button to apply the color.

## HTML Structure

- **Heading (`<h2 id="heading">`)**: Displays the name of the Play Area.
- **Input Field (`<input id="input" type="text">`)**: For entering the user's name.
- **Submit Button (`<button id="submit">`)**: Triggers the name replacement in the heading.
- **Color Picker (`<input type="color" id="colorPicker">`)**: Allows the user to select a color for the container's background.
- **Animation Buttons**: Start moving the boxes when clicked.

## JavaScript Functions

- **`func1()`**: 
  - Retrieves the entered name from the input field, capitalizes the first letter, and updates the heading.
  - Clears the input field after the name is updated in the heading.

- **`myFunction()`**: 
  - Starts the animation by calling `moving_img()` for both `animate1` and `animate2` elements.

- **`moving_img(value)`**: 
  - Animates the movement of boxes (`animate1` and `animate2`) within the container. 
  - The position of each box is updated based on time intervals and the box's ID.

- **`changeBackgroundColor()`**: 
  - Changes the background color of the container to the color selected by the user.

## Installation

1. **Clone or Download the Repository:**
   - You can either clone this repository using Git or download the HTML file directly to your local machine.

2. **Open the HTML File:**
   - Open the `index.html` file in your preferred web browser.

## Demo

The demo will allow you to:
- Enter your name and update the heading.
- Move the animated boxes around by clicking the "Click Here" button.
- Change the background color of the container using the color picker.

## License

This project is open source and available under the [MIT License](LICENSE).
