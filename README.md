# Heardman / Take-home Project / Unity Developer

# Overview

Create a game where the player controls a Shepherd who collects sheep and leads them to a pen.

## Core Mechanics

### Shepherd Movement

- The player controls a Shepherd character who can move around the field by clicking and holding the right mouse button to set a destination point, with the character continuously moving towards the cursor position while the button is held
- Joystick control implementation (optional)

### Sheep Collection

- **Basic Sheep:** When the Shepherd approaches a sheep, it automatically attaches to the Shepherd and follows behind
- **Stubborn Sheep:** Some sheep only attach to the Shepherd if he passes by them with 3 or more sheep already following
- When a sheep attaches to the Shepherd, it should play a short bleating sound effect

### Pen System

- There is a pen area on the field
- When the Shepherd brings sheep to the pen, they are deposited there
- A sound effect should play when sheep are returned to the pen

## Required Features

### Counter System

- Implement a counter that tracks the number of sheep collected in the pen

### Visual Requirements

- Visuals are optional - simple geometric shapes (cubes, squares, etc.) are acceptable

## Technical Requirements

- Implement in Unity
- Include sound effects for sheep attachment and pen return
- Create logic to differentiate between basic sheep and stubborn sheep (3+ requirement)
- Implement a follow system where sheep trail behind the Shepherd

## Deliverables

- Working Unity project with the described gameplay mechanics
- Counter UI displaying collected sheep
- Sound effects implementation
- Basic documentation explaining the implementation approach
