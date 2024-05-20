## Initialize

- Clone repo
- Change port in app.js
- Run npm install
- Server is available to use

## DIY guide

### Initialized project   
- Install nodejs
- Install npm
- Install Visual Studio (if you don't have)
- Create a project file
- Open your project file in VS Code
- Run `npm init`
- Fill in the project details upon initialization
  ![image](https://github.com/Ahosahos/cicd-poc/assets/86953460/658bce31-956c-4217-b5fe-4df147cc57a0)   
  You should get something like this:   
  ![Untitled](https://github.com/Ahosahos/cicd-poc/assets/86953460/b07a77c5-3279-4417-8205-82fb2438e1a9)   
- Type `Yes` or `Y` and your project is ready.

### Add dependencies and install project
- Run `npm install express` to add express.js in your project 
- If there's no node modules in your project yet, you need to run `npm install` or `npm i` to install the dependencies
- Make sure your package.json has express.js as your dependencies
- Any changes made in package.json needs to run `npm install` to reinitialized the script

### Custom start command
- You can have your custom start command by stating it in `package.json` , the concept is `this command by npm, do what?`
- Start command sample: 
![image](https://github.com/Ahosahos/cicd-poc/assets/86953460/642ac8ec-74c2-441e-ac81-989c9c32ebdf)

### Running project
- If you use custom start command, just run `npm {your start command}`
- Else you run `node {your entry file}`

### Testing restfulAPI
- Open a browser or postman, enter "/" to test your first API :)

### To terminate process
- Open current node js/project running terminal
- Press window key + c, or cmd + c in MacOS 



