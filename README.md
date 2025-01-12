# React Setup Cheat Sheet

## Prerequisites
1. **Node.js**: Ensure Node.js version >= 14.0.0 is installed.
   ```bash
   node -v
   ```
2. **npm**: Ensure npm version >= 5.6 is installed.
   ```bash
   npm -v
   ```

## Step-by-Step Setup

### 1. Create a New React Application
Run the following command to create a new React app:
```bash
npx create-react-app my-app
```
Replace `my-app` with your project name.

### 2. Navigate to Your Project
```bash
cd my-app
```

### 3. Start the Development Server
```bash
npm start
```
This launches the app at `http://localhost:3000`.

### 4. Build for Production
To build your app for production:
```bash
npm run build
```
This creates an optimized `build` folder with static files.

### 5. Install Additional Dependencies
#### Commonly Used Packages:
- **React Router** (for navigation):
  ```bash
  npm install react-router-dom
  ```
- **Axios** (for HTTP requests):
  ```bash
  npm install axios
  ```

## Project Structure Overview
```
my-app/
├── node_modules/       # Installed dependencies
├── public/             # Static files
├── src/                # Application source code
│   ├── App.css         # App styles
│   ├── App.js          # Main component
│   ├── index.js        # Entry point
│   └── ...
├── package.json        # Project configuration
└── README.md           # Project documentation
```

## Useful Commands
| Command                | Description                                    |
|------------------------|------------------------------------------------|
| `npm start`            | Starts the development server                 |
| `npm run build`        | Builds the app for production                 |
| `npm test`             | Runs tests                                    |
| `npm install [package]`| Installs a new package                        |
| `npm run eject`        | Ejects the app configuration (use with care!) |

## Troubleshooting
1. **Update npm if `npx` fails:**
   ```bash
   npm install -g npm@latest
   ```
2. **Clear npm cache if errors occur:**
   ```bash
   npm cache clean --force
   ```
3. **Reinstall dependencies if issues persist:**
   ```bash
   rm -rf node_modules
   npm install
   ```

---
Happy coding with React! 🚀
