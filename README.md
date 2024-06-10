1.Install Nodemon Globally:
Make sure you have installed nodemon globally on your system. You can do this using the following command:

npm install -g nodemon

2.Add Nodemon to Your Project:
Alternatively, you can install nodemon as a dev dependency in your project:

npm install --save-dev nodemon

3.Update Package.json Scripts:
If you install nodemon as a dev dependency, you can update your package.json to include a script that uses nodemon. For example:

"scripts": {
  "start": "nodemon src/index.js"
}

4.Then you can run nodemon with:

npm start

5.Verify Installation:
After installation, verify that nodemon is available by running:

nodemon -v
This should display the installed version of nodemon.

5.Check Environment Variables:
Ensure that your environment variables are set correctly, and the path to the global node_modules is included. You can check the PATH environment variable to make sure it includes the directory where npm installs global packages.
On Windows, you can check and update the PATH variable in the Environment Variables settings.

6.Run Your Server
Start your server using nodemon:

nodemon src/index.js

Visit http://localhost:3000 in your browser to see the login form.
