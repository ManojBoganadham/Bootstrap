# What is Node.js and NPM

Node.js helps to bring the power of JS to the desktop. It is based on JavaScript runtime 
engine built on the Chrome V8. It uses an event-driven, non-blocking I/O model which 
makes it very efficient to run JS 
programs on computer. Node.js operates on a single-thread event loop, using non-blocking 
I/O calls, allowing it to 
support tens of thousands of concurrent connections without incurring the cost of 
thread context switching.

NPM (Node Package Manager) manages all the Node modules and packages made availabel by users.

## Node.js and NPM basics

- First, we need to build a *package.json* file.
- *package.json* file contains all the info about our project(like, name. version, author,   dependencies, license etc.), in the form of a json object.
- It can be initialised using `npm init` command in the terminal or the command prompt.
- More about the *package.json* can be found [here](https://d3c33hcgiwev3.cloudfront.net/_4443d45e45735e9bb7e78424745a5ff8_Exercises-Node-NPM.pdf?Expires=1597449600&Signature=joCPOkS19MoQLTP67x7vpsWo0rTot7-IKMGiSo8DgXRasj~v9J7B1HWhM91EW37NzOqx~5vBADHgbXr9S5vwSa5NNbeqZ5JvNlPxuLr5ynmzbN8VvFmRYtFzr37Oa~wqCNzprZIB0OmU2o3GukhfvslpmlpXyDlfhFGAc-f~gUQ_&Key-Pair-Id=APKAJLTNE6QMUY6HBC5A)

- *"start"* in the *"scripts"* object is a command that NPM supports to start somethings when we start the project.
- *"lite* in the *"scripts"* object is just an attribute. 
- In context of our package.json file, the above attributes start the lite-server on the project repository. So, when `npm start` is run in the terminal, it starts a lite-server from the current project repository.
- lite-server will act as an actual server and reflects the changes immediately on the browser without needing to refresh again and again.
- This can be a very useful tool during the development stage.
- The *node_modules* folder can always be recreated by `npm install` command. So, we don't want this folder to be tracked by git.  
