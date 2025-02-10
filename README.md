# Three.js WebGPU with R3F Starter in Vite

## Introduction
This repository provides a starting point for using WebGPU with React Three Fiber in a Vite project. It includes a simple example demonstrating how to set up a WebGPU-powered 3D scene using `@react-three/fiber`, `three`, and `three/webgpu`.

## Versions

1. React: 18
2. React Three Fiber: 8
3. Three.js: 173

## Prerequisites
Make sure you have the following installed before proceeding:
- [Node.js](https://nodejs.org/) (version 16 or later recommended)
- A browser that supports WebGPU (e.g., Chrome Canary with `--enable-unsafe-webgpu` flag)

## Getting Started
### 1. Clone the Repository

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Development Server
```sh
npm run dev
```

This will start the Vite development server. Open your browser and navigate to `http://localhost:5173` to see the WebGPU-powered 3D scene.

## Project Structure
```
r3f-wgpu-tsl-starter/
├── src/
│   ├── App.jsx
│   ├── main.jsx
├── public/
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Configuration
### Enabling WebGPU
Ensure your browser supports WebGPU by enabling it in Chrome Canary:
1. Open `chrome://flags`
2. Enable `Unsafe WebGPU`
3. Restart the browser

## Contributing
Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements.

## License
This project is licensed under the MIT License.
