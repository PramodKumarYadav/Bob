# Project Bob

This project is the playground to learn all good things about automation. The approach of working on this project is two fold.

- Doing a need based learning.
- First make it work, than make it better.

## Conventions

- Folders (PascalCase)
- Files (came-case.txt)
- Names (abstract, one word names - Bob)

## Tools

- Powershell
- VScode

## Important files

- README.md

## Test Goals

- Readable
  - easy to understand
  - easy to maintain
- Maintainable
  - project will grow, and a good design will lead to maintable framework. Quicker fixes, quicker addition of new test case. 
- Scalable
- Trustworthy
- Flexible
  - localhost, CI
  - browsers

## Test Objectives

-[ ] Tests should be atomic (independent tests)
-[ ] Run tests in parallel (scalability)
-[ ] Clear separation of concerns (maintainability)
    - separate your code, config and data and not mix them up. 
-[ ] Tests should not mix intentions with implementation
    - implementation of application logic should go in a separate class (page objects)
    - intentions should stay in tests
-[ ] Version control (Git)
-[ ] Backup (Github)
-[ ] Collaborate (with other team members)
-[ ] Reports
    - CI readable
    - human readable html reports
-[ ] Logging
    - Logging on various levels (debug, info, error)
-[ ] Notifications
    - When your tests run in CI, you would want to know what happened (on slack, via emails)
-[ ] Run your tests in CI (automatically)
    - Triggering  your tests with each Pull request
    - Triggering your tests on a schedule.
    - Manually triggering the builds if the need maybe.

## Setup
For new users, if you want to clone this project to your local, do this.
``` git clone https://github.com/PramodKumarYadav/Bob.git```