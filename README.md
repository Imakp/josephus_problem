# Josephus Problem Simulation

This project simulates the famous **Josephus Problem**, which has historical significance. During the Roman Empire, a group of Jewish soldiers decided to avoid capture by arranging themselves in a circle and devising a system where every nth person would be killed by the next. This process continued until only one person remained. Josephus, a historian, wanted to survive, so he calculated the position to ensure he was the last one alive.

This simulation demonstrates the Josephus problem, allowing users to input the number of people and the step count to visualize how the elimination happens in a circle.

## Project Structure

- **HTML**: Provides a simple interface for users to input the number of people and the step count.
- **CSS**: Defines the styles for a visually appealing layout, particularly for the circular arrangement of people.
- **JavaScript**: Contains the logic to simulate the Josephus problem, animate the eliminations, and determine the survivor.

## How to Use

1. **Enter the Number of People**: Input the total number of people sitting in the circle.
2. **Enter the Step Count**: Input the number of people to skip before eliminating the next person.
3. **Start the Simulation**: Press the "Start Simulation" button. The program will then animate the process of elimination.

### Inputs
- **Number of People**: Specifies how many people are in the circle.
- **Step Count**: Specifies how many people to skip before each elimination.

### Output
- The program visually simulates the eliminations. The final survivor will be displayed at the end of the simulation.

## Code Overview

### HTML

The `index.html` file provides the structure for the user interface:
- Input fields for the number of people and step count.
- A section for visualizing the elimination process.

### CSS

The `style.css` file defines styles for the layout, including:
- **Circular layout**: People are positioned in a circle using absolute positioning.
- **Elimination animations**: Smooth transitions that fade out eliminated people.
- **Responsive design**: Ensures that the visualization works on different screen sizes.

### JavaScript

The `script.js` file handles:
- Dynamically creating the circle of people based on user input.
- Positioning people in a circle.
- Implementing the Josephus elimination algorithm.
- Providing visual feedback for eliminations and displaying the final survivor.

## Files Included

- `index.html`: HTML structure for the Josephus Problem simulation interface.
- `style.css`: CSS for styling the interface and circle arrangement.
- `script.js`: Core logic for simulating the Josephus problem.

## Example Usage

To simulate with 7 people and a step count of 3:
1. Enter **7** in the "Number of People" input.
2. Enter **3** in the "Step Count" input.
3. Press **Start Simulation**. 
   - People in the circle will be eliminated based on the step count until only one person remains.

## Josephus Problem Background

The Josephus problem is a theoretical puzzle related to game theory. It can be described as a group of people standing in a circle, where every nth person is eliminated until only one remains. Historically, Josephus had to determine the correct position in the circle to survive the process.

This problem has applications in computer science, particularly in data structures like **Queues** and **Circular Linked Lists**.
