#Agile practices in software development

This is a hometask project for the training.

[![Build Status](https://travis-ci.org/dmitrymushenko/agile_ht.svg?branch=master)](https://travis-ci.org/dmitrymushenko/agile_ht)

##Flow

Project is set up to track pushes and pull requests to master branch, run tests, build and deploy to s3 in case of success.

Build fails if:
* JSHint fails
* Unit tests fail
* E2E tests fail
 
The last successful build can be found [here](http://agile-ht.s3-website-eu-west-1.amazonaws.com/)
