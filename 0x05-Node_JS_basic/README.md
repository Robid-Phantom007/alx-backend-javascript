# 0x05. NodeJS Basics

## General :house:
* run javascript using NodeJS
* use NodeJS modules
* use specific Node JS module to read files
* use process to access command line arguments and the environment
* create a small HTTP server using Node JS
* create a small HTTP server using Express JS
* create advanced routes with Express JS
* use ES6 with Node JS with Babel-node
* use Nodemon to develop faster

## Requirements :page_with_curl:
* Allowed editors: vi, vim, emacs, Visual Studio Code
* All your files will be interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
* All your files should end with a new line
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the js extension
* Your code will be tested using Jest and the command npm run test
* Your code will be verified against lint using ESLint
* Your code needs to pass all the tests and lint. You can verify the entire project running npm run full-test
* All of your functions/classes must be exported by using this format: module.exports = myFunction;
### Provided files
* database.csv
* package.json
* babel.config.js
* .eslintrc.js
#### And
Don't forget to run $ npm install when you have the package.json

## Tasks and Files :heavy_check_mark:
| Filename | Description |
| -------- | ----------- |
| `0. Executing basic javascript with Node JS` | In the file `0-console.js`, create a function named `displayMessage` that prints in `STDOUT` the string argument. |
| `1. Using Process stdin` | Create a program named `1-stdin.js` that will be executed through command line: |
| `2. Reading a file synchronously with Node JS` | Using the database `database.csv` (provided in project description), create a function `countStudents` in the file `2-read_file.js` |
| `3. Reading a file asynchronously with Node JS` | Using the database `database.csv` (provided in project description), create a function `countStudents` in the file `3-read_file_async.js` |
| `4. Create a small HTTP server using Node's HTTP module` | In a file named `4-http.js`, create a small HTTP server using the `http` module: |
| `5. Create a more complex HTTP server using Node's HTTP module` | In a file named `5-http.js`, create a small HTTP server using the `http` module: |
| `6. Create a small HTTP server using Express` | Install Express and in a file named `6-http_express.js`, create a small HTTP server using Express module: |
| `7. Create a more complex HTTP server using Express` | In a file named `7-http_express.js`, recreate the small HTTP server using `Express`: |
| `8. Organize a complex HTTP server using Express` | Obviously writing every part of a server within a single file is not sustainable. Let’s create a full server in a directory named `full_server`. Since you have used ES6 and Babel in the past projects, let’s use `babel-node` to allow to use ES6 functions like `import` or `export`. |

## Author :black_nib:
* Dibor Solomon
