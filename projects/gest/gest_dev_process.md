# Development Process

## Take a task:
1. Read and mark off 'checklist' items also check latest comments.
1. IF the task has no clear 'checklist', ask the team and/or the PM.
1. The Developer should take a task assigned to them or pick one from the top of the ToDo list
1. Each task should have it's own respective branch (feature branch)

## Development:
1. Write test units and integration testing (all the required tests)
1. Refactor when is possible the existent code (be a good [scout](http://pragmaticcraftsman.com/2011/03/the-boy-scout-rule/))
1. Check if the documentation needs to be changed: add or update documentation.
1. if the task will take more time than the expected, we need to communicate the reason of why is taking more time and wait for feedback.
1. Update changelog if a meaningful change has been made (deprecations, updates, critical bugs).

## Issue PR:
1. Run the tests locally
1. Run the build on client (grunt server:dist)
1. Run the app in production mode
1. Test the task in the browser
1. Put a link back to the task the PR is for in the description.
1. If the task involves design or html integration, we need to test the app with browserstack.

## PR review:
1. Read the task
1. Read the code
1. Test the PR
1. Run the tests
1. Check documentation

## Deployment:
1. See your project ReadMe
