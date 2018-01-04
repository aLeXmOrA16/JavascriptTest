# Javascript Evaluation ANSWERS

1. The "===" doesn't make conversion of types, so it would be avoided if using "==" instead.


2. "outer func:  this.foo = bar
   outer func:  self.foo = bar
   inner func:  this.foo = undefined
   inner func:  self.foo = bar"
   
   Because of the scope of the variable "foo". The inner function has no access to that variable and there's no definition of "foo" in it, so looking for "this.foo" is undefined.

   
3. The major advantage of this is that you can have private methods/functions and properties inside that function that can be exposed as a namespace or plugin.


4. "object"
   
   Since there are no arguments passed to the function, the arguments are null and it is an object type.
  
  
5. "undefined"
	
	Because the argument passed is a function and it has not been defined in that moment.


6. "1undefined"

	Because the "f" function is not defined and when concatenating the "undefined" string to "x" int value 1, it takes the whole variable as a string.


7. "false
	true"

	Because the first one has "()", so it's not fulfilling the rule.

8. It is used to run the code in "strict mode". It means, to write "secure" code avoiding bad syntax or undeclared variables, for example.


9. 


10.


11.