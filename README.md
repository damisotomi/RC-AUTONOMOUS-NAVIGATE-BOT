# RC-AUTONOMOUS-NAVIGATE-BOT
A remote-controlled and autonomous navigate robot car that moves from a set point to a user-defined point on a 2D grid with an obstacle detection feature

## WHY IT WAS DEVELOPED
  The robot car was developed as part of my semester project for the mechatronics course during my first year in the mechanical engineering master program at New York University
  
## HOW IT WORKS
  -This robot car has two modes, the first is the autonomous mode while the second is the manual mode.
  
### AUTONOMOUS MODE
  - In the autonomous mode, the robot moves from a point 0,0 on a 2D grid to a user-defined point x,y on the grid and then returns to its initial position.
  - During its movement, it constantly checks for any obstacles located at least 15cm from it.
  - Once it returns to its initial position, the robot then switches to manual mode to be controlled by a remote control
    
### MANUAL MODE
  - The manual mode is only reached from the autonomous mode in two ways
  - The first way the manual mode is reached is when the robot detects an obstacle while it is in autonomous mode. This makes the robot switch to manual mode for the user to manually control
  - The second way the manual mode is reached is when the robot completes its journey in the autonomous mode. At this point, the robot switches to manual mode for the user to control with a remote control

### MICROCONTROLLER AND PROGRAMMING LANGUAGE USED
  - A BS2 Microcontroller from parallax was used to develop this robot.
  - The programming language used was Pbasic 2.5

### Components used
  - Ultrasonic distance sensor - For obstacle detection
  - LED lights - Serve as indicators
  - Manual SPST switch - Serves as Emergency switch
  - BOEBOT from parallax-  Served as the robot's main system
  - Piezo speaker- Served as alarm and brown-out indicator
  - IR Receiver- Worked with the IR remote for manual control
  - Connecting wires
  - LCD - User interface
  - Buttons - Served as an input tool for the user
  - Resistors

### FUTURE IMPROVEMENTS
  - To make the robot autonomously avoid obstacles in its path instead of switching to manual mode upon obstacle detection

### HOW TO USE
  - Connect the robot to  a power source (9v battery preferably)
  - Switch on the emergency switch
  - turn on the switch on the microcontroller board
  - Read LCD for instructions
  - Press button 1 to enter x values and button 2 to exit
  - press button 1 to enter y values and button 2 to exit
  - watch as the robot moves to your set point and returns

### Live demo
https://drive.google.com/file/d/1ybhBMP3laQJZ5tp93_3f1FzZCp5yAXE5/view?usp=sharing
