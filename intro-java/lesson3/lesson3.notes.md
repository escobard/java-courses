# Lesson 3 - Functions

## Functions

### Sample function definition in Java

```
// function to print line
public void println(String x ){
	if(x == null){
		x = "null"
	}
	try{
		ensureOpen();
		textOut.write(x);
	}
	catch(IoException e){

	}
	newLine()
}


// function to print chorus, broken down with comments to explain syntax purpose

// this is an access modifier, defines who can access the declared function
// public acess means anyone can access the function
public 
	
	// this is called the return type, defines what the function is returning
	// the void return type means that nothing is being returned by the function
	void 
	
	//this is the function name, or what we use to call the function
	chorus(){
	// print out 1 line of chorus
	System.out.println("Once I had a love and it was a gas");
}
```

### Calling a function

```
// this can be called the same way in as in javascript, printing the chorus output

chorus();
```

### Function parameters

- The argument variable must be declared by type within the argument syntax
```
public void greeting(
	
	// this defines the type of the variable expected to be passed as an argument
	String 
	
	// this defines the name of the variable, which can be used within the function scope (like JS)
	location
	){
	System.out.println("Hello," + location);
}
```

### Multiple parameters

```
public void greeting(int width, int height, boolean inColor){
	....
}


// function call
printPhoto(30, 40, true)
```

### Return values

- the return types defines what the function is supposed to RETURN
- void is used if the function is not returning anything, it doesn't create an output for us to interact with in our program
```
public void functionName(){
	// internal block of code - does not return anything, useful for connection functions together
	// like multiple .println outputs, similar to console.logs in js
}
```
- changing the return value to any other variable type, expects the function to return the type of data
```
public String functionName(){

	//
}
```

- returning the function requries the following syntax
```
// requires a variable type, declaring the expected returned data type from the function call
int returnedLikes = likePhoto(0, "Nice color!", false);
```

- we can return calculated change with the following syntax:
```
// Define a function with the name and parameters: makeChange(double itemCost, double dollarsProvided)
// Calculate and return the calculated change which should be the dollarsProvided minus the itemCost

// Remember to return a value you need 1) a return type and 2) a return statement
public double makeChange(double itemCost, double dollarsProvided){
    // variable MUST be declared first, can't be declared AND returned like in js
    double calculateChange = dollarsProvided - itemCost;

    // variable can only be returned AFTER the variable is declared
    return calculateChange;
}

```

### Casting

- 