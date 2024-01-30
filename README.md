## Download & Install

1. Visual Studio
2. Git & Node
```
brew install git
```

## Getting Started

In your terminal
```
// 1. Create a directory
mkdir hello-world-web-app

// 2. Go to the directory
cd hello-world-web-app

// 3. Create package.json
npm init -y 

// 4. Install React & React scripts
npm install react react-dom
npm install react-scripts
// Copy n paste this scripts block in package.json
"scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
},

// 5. Install Typescript
npm install --save-dev typescript

// 6. Create typescript config
npx tsc --init
// Copy paste tsconfig.json here to your tsconfig.json

// 7. Create .ignore
touch .gitignore
// Open .gitignore and add the word "node_modules" in the file

// 8. Initialize Git
git init

// 9. Create index.html and index.tsx files
touch public/index.html
touch src/index.tsx

// 9. Now run your local server
npm start
// It should open a browser with your Hello World project!
```
