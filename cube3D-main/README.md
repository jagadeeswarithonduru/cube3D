# Rubik's Cube Visualizer and Solver

An interactive 3D Rubik's Cube visualization tool built with Python and Matplotlib. This application allows users to manipulate a virtual Rubik's cube using both mouse and keyboard controls.

## Features

- 3D visualization of a Rubik's cube
- Interactive controls (mouse and keyboard)
- Face rotation animations
- Cube scrambling
- Move history tracking
- Status display
- Color-coded interface

## Requirements

- Python 3.x
- NumPy
- Matplotlib

## Installation

1. Clone this repository:
```bash
git clone https://github.com/jagadeeswarithonduru/cube.git
cd cube4
```

2. Create and activate a virtual environment (recommended):
```bash
python -m venv .venv
source .venv/bin/activate  # On Linux/Mac
# or
.venv\Scripts\activate  # On Windows
```

3. Install the required packages:
```bash
pip install numpy matplotlib
```

## Usage

Run the program:
```bash
python cube4
```

### Controls

#### Mouse Controls:
- Click colored buttons for clockwise rotations:
  - U (White) - Up face
  - D (Yellow) - Down face
  - F (Green) - Front face
  - B (Blue) - Back face
  - L (Orange) - Left face
  - R (Red) - Right face
- Click gray buttons for counter-clockwise rotations
- Action buttons:
  - Scramble - Randomly scrambles the cube
  - Reset - Returns the cube to solved state

#### Keyboard Controls:
- Lowercase letters for clockwise rotations:
  - `u` - Up face
  - `d` - Down face
  - `f` - Front face
  - `b` - Back face
  - `l` - Left face
  - `r` - Right face
- Uppercase letters for counter-clockwise rotations (U, D, F, B, L, R)
- Other keys:
  - `s` - Scramble
  - `r` - Reset
  - Arrow keys - Rotate view
  - `x` - Solve (placeholder for future implementation)

## Project Structure

- `cube4` - Main program file containing:
  - `Cubelet` class - Represents individual cube pieces
  - `RubiksCube` class - Manages cube state and operations
  - Visualization and interaction functions

## Features to be Implemented

- Solving algorithm implementation
- Save/load cube states
- Move sequence recording and playback
- Pattern generation
- Solution hints

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.
# cube3D
