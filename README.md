#Node-Jasmine-seed

Seed project for testing JavaScript projects using the official [Jasmine Node module](https://www.npmjs.com/package/jasmine) (and therefore the latest Jasmine version), with verbose test reporting using [jasmine-spec-reporter](https://www.npmjs.com/package/jasmine-spec-reporter). 

I like detail, I like the command line, and I like to see exactly which tests are passing as well as which ones are failing. I find the report satisfying and it provides another way for me to feel connected with my codebase and test suite. I also prefer to use the latest Jasmine version which rules out using the jasmine-node module. 


###Prerequisites

[NodeJS](https://nodejs.org/en/)


###Usage

Clone the repo: ```git clone git@github.com:forty9er/node-jasmine-seed.git``` 

Install the required modules ```npm install```

To run the test script, simply use the ```npm test``` command from inside your project.

Right now, I also like to combine this with [nodemon](https://www.npmjs.com/package/nodemon), [TMUX](https://tmux.github.io/) and [Vim](http://www.vim.org/), which provides a powerful JavaScript TDD environment.
