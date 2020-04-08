Changelogger

An easy way to generate a changelog up to date.

You might execute this script with Jenkis or even with your Git hooks

In my case I use Jenkins for deploy my application and create the artifactory. Before packagin my app I run this script to keep tracking Version and Changelog, this file is going to be seen in the url like /changelog

For generate this file you need to execute this command

$ changelogger > changelog 

With this simple script you should be able to track every event in your application, in my case a run the command into the develop's branch.

