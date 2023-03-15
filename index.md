# NPM Documentation

## Rick Stacey

1. What is NPM? What does it do? Why is it an important tool?
NPM stands for Node Package Manager, it is a library that stores, accesses, and registers Javascript software packages. When accessed from the command line, it allows you to install and manage packages

2. What problems does NPM Slove? 
NPM solves the problem of the complexity that often comes with dependencies and package management, such as creating libraries, dependencies, and connecting to git.

3. Describe the 3 main parts of NPM.?
The Website, which can be used to discover packages and manage other aspects of the experience. The Command Line Interface, which is how developers interact with the NPM, and the registry a large public database of javascript software accessible via npm.

4. What is the package.json file?
A file written in json that which helps define functional attributes of a project like shown:
![A package.json doc](Screenshot (433).png)

5. What is the scripts section of the package.json file? How do you use it? What are the default commands, and how do you use your own?
Pretty self explanatory, the scripts section gets stores the sections of the package.json file. You use it to add and organize commands for the app to run. Like start and test, which if memory serves are the default commands. You use your own by simply definining them in the section.

6. What are dependencies? What does this section define? What are dev dependencies? Why is it important to define dev dependencies vs dependencies?
Dependencies are modules that are needed to run the program. The dependency section defines the dependencies installed. Dev Dependencies are dependencies only for development rather than runtime. And its important to define them because dev dependencies 

7. How do you install dependencies? Where do dependencies get installed?
By using the NPM install command, and they wind up in the library, most typically in the directory

8. When running scripts with NPM, where does NPM look (path) for the dependencies of those scripts?
Typically, it looks in the package.json file, underneath the scripts section

9. Name 3 NPM commands, and why they are important.
npm install = Installs dependencies
npm start = runs the start script
npm test = runs the test script
