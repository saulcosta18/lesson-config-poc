# Lesson Config POC

## config.yml
General lesson configuration:
* Course name
* Course icon
* Stack snapshot to use

## files/
Files copied to `/root/sandbox` in coding environment.

## steps/
Ordered markdown files to use as steps with custom instructions syntax.

## tests/
Test subdirectories. Each subdirectory (e.g. tests/1) can be called whatever you'd like and `1` is used to link instructions to these tests.

## tests/1/config.yml
Configuration file specifying tests (in this case, use Python unit tests to run test1.py and assign a graded weight of 10 points).
