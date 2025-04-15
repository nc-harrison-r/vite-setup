# AUTOMATED REACT SETUP ⚛️

- To create a react app, navigate to the folder in which the new repository folder will be created. Then run:

- ```npx create-react-app <app-name>```
- ```cd app-name```
- ```npm start``` ``` //this will open the app in the browser.```

Then run the...
MEGA SHELL COMMAND for clearing out the react app
    
```bash
rm ./public/favicon.ico ./public/logo192.png ./public/logo512.png ./public/manifest.json ./public/robots.txt; 

echo 'import "./App.css";
function App() {
  return <div className="App"></div>;
}
export default App;' > ./src/App.js; 

echo '<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    <meta
      name="description"
      content="Web site created using create-react-app"
    />
    <title>React App</title>
  </head>
  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>
    <div id="root"></div>
  </body>
</html>' > ./public/index.html;

echo '.App {
  text-align: center;
}' >./src/App.css;

rm ./src/App.test.js ./src/logo.svg ./src/reportWebVitals.js ./src/setupTests.js; 

echo 'import React from "react";
import ReactDOM from "react-dom/client";
import "./index.css";
import App from "./App";
const root = ReactDOM.createRoot(document.getElementById("root"));
root.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>
);' > ./src/index.js 
```
Now everything should be clear and ready for front-end-making. ✅
