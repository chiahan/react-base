# Create React Project without IDE

## Installation (macOS)

Install Node.js and NPM
```
node -v
npm -v
```

## Initialize a React project
npx create-react-app react-base
cd react-base

- src/App.js
```js
import React from 'react';

const App = () => {
  return (
    <div>
      <h1>Hello world</h1>
    </div>
  );
};

export default App;
```
## Start the development server
```
npm start
```
## Test
```
http:///localhost:3000
```
---
Reference: [Building a React app from scratch](https://medium.com/womenintechnology/building-a-react-app-from-scratch-a-step-by-step-guide-2a42a4be41fc)
