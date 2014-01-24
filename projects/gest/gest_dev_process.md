# Gest In Time Development Process

## Take a task:
1. Read the AC of the task and the Epic task related
1. IF the task has no clear AC, ask to the team and/or the PM.
1. The Developer should take a task from the top of the ToDo list
1. Each task should have the respective branch (feature branch)

## Development:
1. Write test units and integration testing (all the required tests)
1. Refactor when is possible the existent code
1. Check if the documentation needs to be changed: add or update documentation.
1. if the task will take more time than the expected, we need to communicate the reason of why is taking more time and wait for feedback.
1. Update changelog if a meaningful change has been made (deprecations, updates, critical bugs).

## Issue PR:
1. Run the tests in client and server
1. Run the build on client (grunt build:server)
1. Run the app in production mode
1. Test the app
1. If the task involves design or html integration, we need to test the app with browserstack.

## PR review:
1. Read the task
1. Read the code
1. Test the PR
1. Run the tests
1. Check documentation

## Deployment:
1. Run the tests
1. deploy to staging (https://bitbucket.org/gestintime-ondemand/gestintimewebclient/wiki/Deploy%20instructions)
