# Sorting Algorithm Visualization

## Overview

This project provides a dynamic **visualization** of sorting algorithms using Python and the **Pygame** library. It allows users to interactively observe how sorting algorithms operate by visually representing the movement and comparison of data elements.

The program supports:
- **Bubble Sort**
- **Insertion Sort**
  
Users can toggle between these sorting methods, choose sorting directions (ascending/descending), and reset the data for multiple visualizations.

---

## Features

- **Real-time Visualization**: Displays each step of the sorting process, with colors distinguishing the compared elements.
- **User Controls**: Allows dynamic interaction to switch between sorting algorithms, directions, and reset the visualization.
- **Interactive GUI**: Built with Pygame, offering an intuitive and responsive interface.

---

## How to Run the Program

### Prerequisites
Ensure you have Python and Pygame installed:
```bash
pip install pygame
```

### Running the Program
Save the file as sorting_algorithm.py.
Run the script:
```bash
python sorting_algorithm.py
```

## How It Works
### Core Components:

DrawInformation Class: Handles rendering the GUI, including blocks representing data, text, and titles.
Sorting Algorithms:
    Bubble Sort:
        Iteratively compares adjacent elements.
        Swaps them if they are out of order.
    Insertion Sort:
        Builds a sorted portion of the list by inserting each new element into its correct position.
Visualization:
    The elements are displayed as blocks of varying heights.
    Green: Highlights the current comparison.
    Red: Indicates the element being swapped.
Dynamic User Interaction:
    The main loop listens for user input to control sorting, reset, or quit actions.

### File Structure

  DrawInformation Class: Defines the drawing window and layout.
  generate_starting_list Function: Creates a random list of numbers for sorting.
  bubble_sort Generator: Implements the Bubble Sort algorithm with visualization.
  insertion_sort Generator: Implements the Insertion Sort algorithm with visualization.
  main Function: Contains the main game loop for handling input, drawing, and executing sorting.

## Author

Christian DeJong

Feel free to modify, expand, or use this project for educational purposes!
