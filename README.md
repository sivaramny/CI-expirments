Travis CI
=========
Pre-requisites:

  - Github
  - Basic NodeJS (NPM)
  - GruntJS

Official Site: https://travis-ci.org/

Steps to create a simple Hello example with travis-ci
------------------------------------------------------
1. Create the below files (locally, later need to create repo in git)
    a) hello.js : Sample hello world with node running on localhost:1337
    b) package.json: Contains required packages
    c) Gruntfile.js : JavaScript Task Runner
   Download all the related packages using : npm install
   Run the file: grunt (eg: run two times for fail & pass cases)

2. Hello World With Travis CI
    a) .travis.yml : Contains essential information about the environment and configurations for the build to run.
    b) create remote repostiroy in git
       Ref:https://github.com/new
       ```
       git init
	     git commit -m "first commit"
       git remote add origin git@github.com:[username]/[repository].git
       git push -u origin master

       ```
3. Log in to Travis CI and authorize Travis CI to access your Github account. 

Ref:
- http://code.tutsplus.com/tutorials/travis-ci-what-why-how--net-34771
- http://docs.travis-ci.com/user/for-beginners/
