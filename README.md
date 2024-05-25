# Sorting Visualizer

## Overview
The **Sorting Visualizer** is a web application that visually demonstrates various sorting algorithms. This project helps users understand how different sorting algorithms work by visualizing their process step-by-step. 

## Features
- **Algorithms Visualized**: Bubble Sort, Insertion Sort, Selection Sort, Merge Sort, Quick Sort
- **Adjustable Array Size**: Users can change the size of the array to see how the algorithms perform with different data volumes.
- **Adjustable Speed**: Users can control the speed of the visualization to better observe the sorting process.
- **Dynamic Array Generation**: Users can generate a new array of random values at any time to test the sorting algorithms.


### index.html
The main HTML file that structures the layout of the web application. It includes a navigation bar with buttons for each sorting algorithm, controls for adjusting the array size and speed, and a container to display the array.

### style.css
The CSS file that styles the application, including the layout, buttons, sliders, and array container.

### scripts/
This directory contains all the JavaScript files responsible for the functionality of the application:

- **main.js**: Handles the initialization, array generation, and user interactions.
- **visualizations.js**: Contains common functions and utilities for visualizing the sorting process.
- **bubble.js**: Implements the Bubble Sort algorithm and its visualization.
- **insertion.js**: Implements the Insertion Sort algorithm and its visualization.
- **selection.js**: Implements the Selection Sort algorithm and its visualization.
- **merge.js**: Implements the Merge Sort algorithm and its visualization.
- **quick.js**: Implements the Quick Sort algorithm and its visualization.

## How to Run
1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/sorting-visualizer.git
    ```


## Usage
1. **Select a Sorting Algorithm**: Click on any of the buttons labeled "Bubble", "Insertion", "Selection", "Merge", or "Quick" to select the desired sorting algorithm.
2. **Adjust Array Size**: Use the "Size of Array" slider to adjust the number of elements in the array.
3. **Adjust Speed**: Use the "Speed of algorithm" slider to control the speed of the visualization.
4. **Generate New Array**: Click on the "Generate Array" button to create a new random array.
5. **Visualize Sorting**: Once an algorithm is selected and the array is generated, the sorting process will be visualized within the array container.

