# coverage-guard
A tool to guard coverage 

## Motivation 
I some case in not TDD SDLF the process to develop is
- write code that respect tha active task, 
- write test. 
- write test of new code parts, 
- write test after some refactor

In a large code base it's difficult monitor if some critical aspect of production code was covered from test, functional, unit, or integration. So the percentage is the same but the lines coverage from the test no.

## Idea 
The idea is to develop a tool for monitoring coverage of production code. 

To guard that a particular part of the code it's covered from the tests. 

This tool may be shipped with docker so that each programming language it maybe use it.
