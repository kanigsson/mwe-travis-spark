# mwe-travis-spark

Example project that shows how to use GNAT Community 2018 in Travis CI.

[![Build Status](https://travis-ci.com/kanigsson/mwe-travis-spark.svg?branch=master)](https://travis-ci.com/kanigsson/mwe-travis-spark)

## Step 1

Enable Travis-CI on your repository. This can be done by going to your settings on [travis-ci.com](travis-ci.com).

## Step 2

Copy the `.travis.yml` file and the contents of the `scripts` folder to your repository. You need to adapt the end of the `.travis.yml` to your project. Pushing these files via a new commit to a repository should trigger a build, which you can see on the travis interface.

## Step 3

Add the badge to your project. In the Travis-CI interface, click on the build status logo. It will open a dialogue where you can select Markdown syntax, that you can then copy-paste to your `README.md`.
