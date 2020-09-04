# ReactJS my-app
## Need Nodejs installed in your desktop
#In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Commands in Order to Deploy
npm install gh-pages --save-dev<br />
git init <br />
git remote add origin https://github.com/  (--to your path)<br />
#Important addition in file 
In package.json add in first bracket "homepage": "https://username.github.io/reponame"<br />
And in scripts add "predeploy": "npm run build","deploy": "gh-pages -d build",<br />
git status<br />
git add .<br />
git commit -m "anything"<br />
npm run deploy<br />
git push -u origin master<br />
