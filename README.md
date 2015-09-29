# RCScript

An interpreted language implemented in C.

## Build

Compiled with MinGW for Windows
http://www.mingw.org/

## Goal

Interpret a basic hello world / read input / if statement program such as

'''

name = input()

print("Hello " + name)

if name == "Dave" then
	print("Which Dave?")
end

'''

etc.

## Planned Features
### Basic Math
### Variables
### If Statements
### Key Input

## Order Of Operations
* Convert String to Tokens
* Check If Tokens Are a Valid Expression
* Evaluate Parenthesis (Convert To Tree?)