# 🧩 Rubik's Cube Simulation

A fully interactive 3D Rubik's Cube simulation built with React.

![Rubik's Cube Simulation](https://api.placeholder.com/600/400)

## ✨ Features

- 🎮 Realistic 3D cube visualization using CSS 3D transforms
- 🔄 Fully functional cube rotation mechanics
- 🔤 Standard Rubik's Cube notation support (U, D, F, B, L, R)
- 🔁 Clockwise and counterclockwise rotations for each face
- 🌊 Smooth animations for all cube movements
- 🎨 Accurate color tracking for each cube piece
- 📱 Responsive design

## 🚀 Demo

[Live Demo](https://example.com/rubiks-cube-demo) (Coming soon!)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/Snapdragon8g2/SolveTheCube.git
cd SolveTheCube
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:3000`

## 🎮 Usage

The cube can be manipulated using the buttons below the cube:

- **U**: Rotate the upper face clockwise
- **U'**: Rotate the upper face counterclockwise
- **D**: Rotate the down face clockwise
- **D'**: Rotate the down face counterclockwise
- **F**: Rotate the front face clockwise
- **F'**: Rotate the front face counterclockwise
- **B**: Rotate the back face clockwise
- **B'**: Rotate the back face counterclockwise
- **L**: Rotate the left face clockwise
- **L'**: Rotate the left face counterclockwise
- **R**: Rotate the right face clockwise
- **R'**: Rotate the right face counterclockwise

## ⚙️ How It Works

The simulation uses React's state management to keep track of each cube piece's position and colors. When a face rotation is performed:

1. The appropriate pieces are identified based on their positions
2. Their positions are recalculated using 3D rotation matrices
3. The colors on each face are updated to maintain accuracy
4. CSS transitions provide smooth animations between states

## 📁 Code Structure

- `RubiksCube`: The main component that manages cube state and renders the UI
- `CubePiece`: A component representing each individual piece of the cube
- `COLORS`: An array defining the standard colors for each face
- `rotateFace`: The core function that handles the logic for rotating faces

## 🔮 Planned Features

- 🖱️ Mouse/touch drag controls for cube rotation
- ⌨️ Keyboard shortcuts for moves
- 🔀 Scramble button for random shuffling
- 🧠 Solve button with step-by-step solution
- 📜 Move history and undo functionality
- 🎭 Custom color themes
- 📏 Support for different cube sizes (2x2, 4x4, etc.)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


## 🙏 Acknowledgments

- Inspired by the original Rubik's Cube puzzle invented by Ernő Rubik
- Built with ⚛️ React and CSS 3D transforms
