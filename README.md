# General

Commands used so to install packages:

```
npm install react
npm install react-dom
yarn add @babel/core @babel/cli @babel/preset-env -D
yarn add @babel/preset-react -D
```

In the last command, -D is to set the dependencies as devDependencies.


# Converting with Babel in the terminal

Ads we installed **@babel/cli**, we can use the following command to convert our code in the terminal:

```
<application-root>/node_modules/bin/babel <input> <output>
```


# Generating bundle.js

We generated the file **bundle.js** with the following command:

```
yarn babel src/index.jsx --out-file dist/bundle.js
```


# Creating a 'manual' folder and a folder with the content generated with the command 'npx create-react-app'

I created a folder and moved the previous created files and directories (except README.md, .git and .gitignore) to this folder. Then I created a new React app with the command 'npx create-react-app'.


# Comments of the teacher during the class

Teacher commented about:

- Chakra UI (in respect to already builded components)
- Material design (in respect to already builded components);
- CSS property align-items, that teacher commented that can align items vertically.