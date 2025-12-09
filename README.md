# 🎮 Game Development Engine

A powerful 2D game engine with physics simulation, built with C++ core and JavaScript scripting layer. Features WebGL rendering, cross-platform support, and comprehensive asset management.

## ✨ Features

- 🎯 **Physics Engine**: Realistic 2D physics simulation
- 🎨 **WebGL Rendering**: Hardware-accelerated graphics
- 📜 **JavaScript Scripting**: Easy game logic scripting
- 🌐 **Cross-Platform**: Web, Desktop, Mobile support
- 🎵 **Audio System**: 3D positional audio
- 🎬 **Animation System**: Sprite and skeletal animations
- 📦 **Asset Management**: Efficient resource loading
- 🔧 **Scene Editor**: Visual scene editor
- 🐛 **Debug Tools**: Built-in debugging utilities
- 📊 **Performance Profiler**: Real-time performance monitoring

## 🛠️ Tech Stack

### Core
- **C++17** for engine core
- **WebAssembly** for web deployment
- **Emscripten** for C++ to WASM compilation
- **SDL2** for window management
- **OpenGL ES 2.0** for rendering

### Scripting
- **JavaScript/TypeScript** for game logic
- **V8 Engine** integration
- **Hot Reload** support

### Tools
- **CMake** for build system
- **Docker** for containerization
- **GitHub Actions** for CI/CD

## 🚀 Getting Started

### Prerequisites
- C++17 compatible compiler
- CMake 3.15+
- Emscripten SDK (for web builds)
- Node.js 18+ (for scripting tools)

### Installation

```bash
# Clone the repository
git clone https://github.com/L8ab/game-engine.git
cd game-engine

# Build the engine
mkdir build && cd build
cmake ..
make

# Or for web build
emcmake cmake ..
emmake make
```

### Quick Start

```javascript
// Example game script
import { Engine, Scene, Sprite } from '@l8ab/game-engine';

const engine = new Engine({
  canvas: document.getElementById('game-canvas'),
  width: 800,
  height: 600
});

const scene = new Scene();
const player = new Sprite('player.png', { x: 100, y: 100 });

scene.add(player);
engine.loadScene(scene);
engine.start();
```

## 📁 Project Structure

```
game-engine/
├── src/                    # C++ source code
│   ├── core/               # Engine core
│   ├── physics/            # Physics engine
│   ├── rendering/          # Rendering system
│   └── audio/              # Audio system
├── bindings/               # JavaScript bindings
├── examples/               # Example games
├── tools/                  # Development tools
│   ├── editor/             # Scene editor
│   └── profiler/           # Performance profiler
└── docs/                   # Documentation
```

## 🎯 Key Features

### Physics Engine
- Box2D integration
- Collision detection
- Joints and constraints
- Force and impulse system
- Ray casting

### Rendering System
- Sprite batching
- Texture atlas support
- Shader system
- Particle effects
- Post-processing effects

### Asset Pipeline
- Texture compression
- Audio format conversion
- Sprite sheet generation
- Asset bundling
- Lazy loading

## 🎮 Example Games

- **Platformer**: 2D side-scrolling platformer
- **Top-Down Shooter**: Action-packed shooter
- **Puzzle Game**: Match-3 puzzle game
- **Racing Game**: 2D racing game

## 📊 Performance

- 60 FPS on modern hardware
- < 16ms frame time
- Efficient memory management
- Optimized draw calls
- Texture streaming

## 🔧 Development Tools

### Scene Editor
- Visual scene composition
- Real-time preview
- Property inspector
- Animation timeline
- Physics debugging

### Profiler
- Frame time analysis
- Memory usage tracking
- Draw call statistics
- Performance graphs

## 🧪 Testing

```bash
# Run unit tests
make test

# Run integration tests
make test-integration

# Run performance benchmarks
make benchmark
```

## 📚 Documentation

- [Getting Started Guide](docs/getting-started.md)
- [API Reference](docs/api-reference.md)
- [Tutorials](docs/tutorials.md)
- [Best Practices](docs/best-practices.md)

## 🤝 Contributing

We welcome contributions! Please read CONTRIBUTING.md first.

## 📝 License

MIT License - see LICENSE file for details

## 👤 Author

**L8ab**
- GitHub: [@L8ab](https://github.com/L8ab)
- Email: L8ab@proton.me
- Instagram: [@L8ab](https://www.instagram.com/L8ab)

---

**POWERED BY L8AB** ⚡

