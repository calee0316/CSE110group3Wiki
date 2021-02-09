# Team Internet Bowser

## Testing
For the testing part of our pipeline we decided to use Jest. Our pipeline installs jest, then finds all files in the timer directory that end in test.js. It will run all these test files and show the resuls.

## Documentation Generation
For Documentation generation, we are using JSDocs. Our pipeline will install node, install JSDocs, then run it on our index.js file within the timer directory. The documentation is generated in the source directory. 

## Linting
We are using ESLint to lint our JavaScript files and stylelint to lint our CSS files. Our pipeline installs ESLint and stylelint, then runs ESLint on all files ending in .js in the timer directory. Then stylelint is run on all css files in the css directory.

[[/admin/pipeline/diagram.png]]