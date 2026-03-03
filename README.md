# WebAssembly in React

A React application demonstrating WebAssembly integration using AssemblyScript, built with [Vite](https://vitejs.dev/).

## Available Scripts

In the project directory, you can run:

### `npm start`

Builds the WebAssembly module and runs the app in development mode.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

Changes will be instantly reflected via Hot Module Replacement (HMR) without a full page reload.

### `npm run build`

Builds the WebAssembly module and creates a production build to the `build` folder.

It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include hashes for caching.

### `npm run preview`

Locally preview the production build. Run this after `npm run build`.

The preview server will start at [http://localhost:4173](http://localhost:4173).

### `npm run asbuild`

Compiles the AssemblyScript module to WebAssembly.

This generates the `public/as-api.wasm` file used by the application.

### `npm run jsstart`

Starts the Vite development server without building the WebAssembly module.

Use `npm start` instead to build both the WASM and start the dev server.

### `npm run jsbuild`

Builds the React application for production without building the WebAssembly module.

Use `npm run build` instead to build both the WASM and React app.

## Project Structure

- `src/` - React application source code
- `assembly/` - AssemblyScript source code for WebAssembly modules
- `public/` - Static assets (including compiled WASM files)
- `vite.config.js` - Vite configuration

## Learn More

- [Vite Documentation](https://vitejs.dev/)
- [React Documentation](https://reactjs.org/)
- [AssemblyScript Documentation](https://www.assemblyscript.org/)
