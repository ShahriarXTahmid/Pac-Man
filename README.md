**Pac-Man Java Game**

A classic Pac-Man game implementation in Java using Swing framework for graphical rendering. This project faithfully recreates the nostalgic arcade experience with smooth character movement, ghost AI, collision detection and score tracking.

**#Game Overview**
This Pac-Man implementation features all the core elements that made the original game an arcade legend:

1. A maze with walls, pathways, and collectible dots
2. Pac-Man character controlled by arrow keys
3. our colored ghosts with basic AI movement patterns
4. Score tracking and life system
5. Game over and restart functionality

**#Features**
**#Core Gameplay**
1. Character Control: Navigate Pac-Man using arrow keys (UP, DOWN, LEFT, RIGHT)
2. Collision Detection: Precise collision handling with walls, ghosts, and collectibles
3. Score System: Points awarded for each dot collected
4. Life System: Three lives with reset upon ghost collision
5. Game States: Pause/resume functionality (P/R keys) and game over detection

**#Visual Elements**
1. Custom Graphics: Traditional Pac-Man sprites for characters and ghosts
2. Maze Design: Faithful recreation of the classic Pac-Man maze layout
3. Dynamic Rendering: Smooth animation through Java Swing's painting system
4. UI Elements: Score and life counter display

<img width="1920" height="1080" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/48792d0e-bea9-4348-9d9f-01ee983e0684" />


**#Technical Implementation**
1. Object-Oriented Design: Clean class structure with Block class representing game entities
2. Timer-Based Game Loop: 50ms refresh rate for smooth gameplay
3. Event-Driven Architecture: Keyboard input handling for responsive controls
4. Resource Management: External image loading for game assets

**#Game Mechanics**
**Movement System**
Pac-Man moves at a constant speed of 8 pixels per frame (tileSize/4). The movement system includes: Direction-based velocity updates, Wall collision prevention and Smooth navigation through maze corridors.

**#Ghost Behavior**
**The four ghosts (red, pink, blue, and orange) feature:**
1. Random direction changes upon wall collisions
2. Special behavior at specific maze locations (particularly at row 9)
3. Independent movement patterns
4.4 Reset to starting positions after Pac-Man loses a life


**#Installation and Execution**

**Requirements**
1. Java Development Kit (JDK) 8 or higher (VS Code, Eclipse or Intellij IDEA)
2. Image resources in the same directory as class files:
Basicallly download all the files provided here.

**Controls**

*Arrow Keys:* Control Pac-Man's direction

*P Key:* Pause the game

*R Key:* Resume the game

*Any Key after Game Over:* Restart the game





