## Alura TypeScript Course - Part 1: AluraBank

This repository contains the forked code for Part 1 of the TypeScript Course offered by [Alura](https://www.alura.com.br/), part of (Boticário's Desenvolve Program)[https://desenvolve.grupoboticario.com.br/]. It covers the basics of TypeScript and focuses on building a simple banking application called AluraBank.

### Prerequisites

Before running the application, make sure you have the following installed:

- Node.js (version 12 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/alurabank.git
   ```

2. Navigate to the project directory:

   ```bash
   cd alurabank
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

### Usage

To start the application, run the following command:

```bash
npm start
```

The application will compile the TypeScript code and start the Lite Server, which will serve the application on `http://localhost:3000`.

### Scripts

- **test**: Runs the tests for the application.
- **server**: Starts the Lite Server to serve the application from the `dist` directory.
- **start**: Concurrently runs the `watch` and `server` scripts.
- **compile**: Compiles the TypeScript code.
- **watch**: Watches for changes in the TypeScript files and automatically recompiles them.
