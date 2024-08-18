Deploying a website locally with Express is fast and easy.

I'll show you how to install node.js and express and get a simple hello world application up and running. This tutorial is tailored towards Mac users. All steps below are performed from the CLI.

As a Customer Engineer, building demos reliably and quickly is a must. For example, if I wanted to showcase how to use a REST API, like send a text message with Twilio's SMS API, I can quickly do that with Express.

We'll use homebrew If you don't have hombrew installed I recommend installing it. 

To install homebrew, from your main directory enter the following:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Step 1: Install node
```
brew install node
```
Step 2: Create a new directory and move to that directory
```
mkdir myapp
cd myapp
```
Step 3: Use the npm init command to create a package.json file for your application
```
npm init
```
This command prompts you for a number of things, such as the name and version of your application. For now, you can simply hit RETURN to accept the defaults for most of them, with the following exception:
```
entry point: (index.js)
```
Enter app.js, or whatever you want the name of the main file to be. If you want it to be index.js, hit RETURN to accept the suggested default file name.
Step 4: Install Express in the myapp directory and save it in the dependencies list
```
npm install express
```
Step 5: Search http://localhost:3000 from your web browser.
