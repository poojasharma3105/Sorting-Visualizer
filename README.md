# Sorting Visualizer

A web application that visualizes the most common sorting algorithms (Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, Heap Sort) using dynamic visualizations. The project allows users to interact with and observe how different sorting algorithms work on randomly generated arrays.
Live link to see: https://poojasharma3105.github.io/Sorting-Visualizer/

## Features

- Visualize Sorting Algorithms: See how algorithms like Bubble Sort, Insertion Sort, Merge Sort, Quick Sort, and Heap Sort operate on an array.
- Adjustable Array Size: Control the number of elements in the array.
- Control Algorithm Speed: Adjust the speed at which the sorting algorithm runs.
- Responsive Design: Works well on both desktop and mobile devices.

## Installation

### Prerequisites
- Node.js (if you're running a local server)
- A web browser (for viewing the app)

### Steps to Set Up Locally
1. Clone the Repository
Clone the repository to your local machine using Git:
git clone https://github.com/your-username/sorting-visualizer.git

cd sorting-visualizer

3. Install Dependencies
If you're working on the backend with Node.js or using any packages, install the dependencies:
npm install

4. Run the App Locally
If you have a Node.js server:
npm start

This will run the app locally on http://localhost:3000.

## Usage
Interact with the Sorting Visualizer:
1. Array Size: Use the slider to adjust the size of the array.
2. Algorithm Speed: Adjust the speed of the sorting algorithm using the speed slider.
3. Generate New Array: Click the "Generate New Array!" button to randomly generate a new array of elements.
4. Choose an Algorithm: Click one of the sorting algorithm buttons (Bubble, Insertion, Merge, Quick, Heap) to visualize the sorting process for the selected algorithm.

## Algorithms Supported
The following sorting algorithms are implemented in the project:
1. Bubble Sort: A simple comparison-based sorting algorithm where the largest elements "bubble" to the end of the array after each iteration.
2. Insertion Sort: Builds the sorted array one element at a time by comparing the current element with the previous elements.
3. Merge Sort: A divide-and-conquer algorithm that splits the array into halves, recursively sorts each half, and merges the sorted halves.
4.Quick Sort: Another divide-and-conquer algorithm that selects a "pivot" and partitions the array around the pivot.
5.Heap Sort: Converts the array into a heap and repeatedly extracts the maximum element to create a sorted array.
