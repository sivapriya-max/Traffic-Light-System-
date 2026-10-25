# Traffic-Light-System-
#  Traffic Light System in C

##  Project Description
The Traffic Light System is a simple C programming project that simulates the basic operation of traffic signals. It allows the user to select a traffic light color and displays the corresponding action.

##  Objective
To understand the use of `switch` statements and conditional logic in C programming.

##  Technologies Used
- Programming Language: C
- Compiler: GCC or any C compiler

##  Features
- Displays three traffic light options.
- Red indicates STOP.
- Yellow indicates WAIT.
- Green indicates GO.
- Handles invalid user input.

##  Source Code
The program uses a `switch` statement to identify the selected traffic light and display the corresponding instruction.

##  How to Run
1. Copy the source code into a file named `traffic_light.c`.
2. Compile the program using:

   ```bash
   gcc traffic_light.c -o traffic_light
   ```

3. Run the program:

   **Windows:**
   ```bash
   traffic_light.exe
   ```

   **Linux:**
   ```bash
   ./traffic_light
   ```

##  Sample Output

```text
Traffic Light System
1. Red
2. Yellow
3. Green
Enter your choice: 1
RED - STOP
```

##  Concepts Learned
- Basic C programming
- `switch` statements
- `case` and `break`
- User input using `scanf()`
- Output using `printf()`

##  Future Improvements
- Implement automatic signal switching.
- Add a timer for each signal.
- Develop a hardware-based traffic light system using Arduino.

