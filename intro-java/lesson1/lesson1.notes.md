## Common commands

```
// writes simple string to screen
// can be used to output anything, including calculations
System.out.println('Hello, World')
```
### Important points to note
	- java is case sensitive

## Variables

	- just like with JS, same rules apply here to java variables
	- however, the variable TYPE must be declared on variable declaration
	- for example `int passengers` declares an integer variable

### Number types 
	
	- long : store larger number than integers (numbers longer than 10 digits cannot be stored in int)
	- double: stores an even larger decimal number.

### String types
	- char: accepts a single string character

### Math
	- a double rounds numbers based on the type
	- for example `double accurate = 24/5` would equal 4.8, but is rounded to 4 since no fractions are declared
	- similarily, `double accurate2 = 24/5.0` would equal 4.8.

#### Truncation
	- cutting off the digits to the right of a decimal point.
	- You can do the following:
	```
	double rate = 1.5
	double current = 17
	double future = current * rate = 25.5
	int approx = (int) future = 26 = rounds the number if an int declaration is added
	```
	- vice versa, if declaring a double in the brackets the value is returned as a double, not a decimal

### Comments
	- exactly the same as JS declarations