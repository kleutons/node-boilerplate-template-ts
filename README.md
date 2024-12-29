# NODE BOILERPLATE - TYPESCRIPT EDITION
<img src="./.github/assets/node.Ts.png" alt="Logo" height="300">


### Don't start a new Node project from zero!
### Use this simple **Nodejs** boilerplate with pre-configured **Typescript** in a modern way.

<br />
  <!-- Badges -->
<div align="center">

  [![TypeScript version][ts-badge]][typescript-5-7]
  [![Node.js version][nodejs-badge]][nodejs]

</div>

<br />

# 🚀 Technologies

This code source was developed with the following items:

### 📦 Dependencies

- [typescript][typescript-npm] - Superset for application scale JavaScript development
- [tsx][tsx-npm] - TypeScript Execute (tsx): Enable Node.js to run TypeScript
- [tsup][tsup-npm] - Bundle your TypeScript library with no config, powered by esbuild
- [@types/node][@types/node-npm] - type definitions for node

### 📄 Files

- `.gitignore` - Ignore folders like node_modules
- `.env` - Enviroment variables
- `tsconfig.json` - Typescript configure Options

### ⚡ Scripts

- `npm run build`: Compiles TypeScript files to JavaScript in the build directory.
- `npm run dev`: Runs the server in development mode with environment variables loaded from the .env file.
- `npm run start:build`: Compiles the project and runs the compiled version from the build directory.