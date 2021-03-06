# CI/CD Pipeline
Our CI/CD Pipeline is done in GitHub Actions using .yml files that our Dev team was able to implement. The tools we used in each of these files is specified below. 

## Testing
For the testing part of our pipeline we decided to use Jest. Our pipeline installs jest, then finds all files in the timer directory that end in test.js. It will run all these test files and show the resuls.

## Documentation Generation
For Documentation generation, we are using JSDocs. Our pipeline will install node, install JSDocs, then run it on our index.js file within the timer directory. The documentation is generated in the source directory. 

## Linting
We are using ESLint to lint our JavaScript files and stylelint to lint our CSS files. Our pipeline installs ESLint and stylelint, then runs ESLint on all files ending in .js in the timer directory. Then stylelint is run on all css files in the css directory.


## Diagram of pipeline workflow
[[https://github.com/calee0316/cse110-w21-group3/blob/main/admin/pipeline/diagram.png]]