# Algorithm Visualizer

## Description
Algorithm Visualizer is a RISC-V assembly-based tool designed to demonstrate the insertion sort algorithm visually. Built on the RARS simulator, the visualizer sorts a list of integers and represents them with colour-coded bars, distinguishing between positive and negative numbers easily.

### Technologies Used
- **RISC-V Assembly:** The core programming language for implementing the sorting algorithm and visualization logic.
- **RARS:** The RISC-V Assembly Runtime Simulator used to run and test the program.
- **Java:** Required to execute the RARS simulator.

### Features
- **Insertion Sort:** Visualizes the sorting process using insertion sort.
- **Colour-coded Visualization:**
    - Positive numbers are represented as green bars.
    - Negative numbers are represented as red bars.
    - Selected numbers are represented as blue bars.
- **Step-by-Step Execution:** Allows users to observe how each step of the algorithm moves the elements into place.

Unsorted list of integers vs sorted list of integers: 

![Algorithm Visualizer Start](https://github.com/user-attachments/assets/6cef24ed-ff9c-4fa4-bc90-626739a7d436)
![Algorithm Visualizer End](https://github.com/user-attachments/assets/6cd56f4d-78cf-4973-921a-9ae54e4ae26f)

## Setup & Usage
### Video Overview
The following video provides an example of the Algorithm Visualizer.

[![Watch the video](https://github.com/user-attachments/assets/3f5a69c6-7425-4980-ae68-db9d719f1cc7)](https://github.com/user-attachments/assets/cb4b8771-2df7-4ea2-b692-4522f7d6b40c)

### Setup Instructions
To set up the Algorithm Visualizer, follow these steps:

1. **Prerequisites:**
    - Ensure Java is installed (JDK 8+).
    - Download the RARS simulator: RARS v1.6.

2. **Clone the repository:**
    - Open your terminal and run the following command: git clone https://github.com/JillFerence/Algorithm-Visualizer.git

3. **Run the Algorithm Visualizer:**
    - Download the rars1_6.jar file and place it in the same folder as the visualizer.s file.
    - Open a terminal and navigate to the project folder.
    - Run the visualizer using the following command: java -jar rars1_6.jar visualizer.s
      
With these steps, you should be ready to start using the Algorithm Visualizer tool!

## Credits
This project was completed for credit in CMPT 229 - Computer Organization and Architecture I at the University of Alberta.
- **Developer**: Jill Ference  
  [GitHub Profile](https://github.com/jillference) | [LinkedIn](https://linkedin.com/in/jillference)
- Farel Nicholas Adrian Lukas for sorting algorithm visualizer functions tester base code.
- Austin Crapo and Taylor Zowtuk for visualizer graphics base code.
