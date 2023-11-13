# Wordscript

This is a repository for a transpiler for the Wordscript language into Java.


An interpreter will be developed in the future.

Wordscript an interpreted language where all keywords and operators are fully spelled out for maximum readability.

Even 3 year olds should be able to read Wordscript.


# Syntax
    
## Keywords and Operators
    
- if
- else
- else_if
- open_parenthesis
- close_parenthesis
- colon
- switch
- open_curly_brace
- close_curly_brace
- typecast
- to
- dot
- equals
- equals_equals
- double_quotation_marks
- single_quotation_marks
- import  
- everything  
- from  
- semicolon  
- open_square_bracket  
- close_square_bracket  
- minus_minus  
- plus_plus  
- minus  
- plus  
- asterisk  
- back_slash  
- forward_slash_equals  
- asterisk_asterisk  
- hashtag (comment to the left of a line of code)  
- begin_documentation_block  
- end_documentation_block  
- function  
- private  
- public  
- case  
- break  
- continue  
- percent  
- back_slash_equals  
- asterisk_equals  
- plus_equals  
- minus_equals  
- percent_equals  
- all_functions  
- all_classes  
- comma  
- and_and  
- pipe_pipe  
- and  
- pipe  
- pipe_equals  
- and_equals  
- caret_equals  
- left_angle_bracket_left_angle_bracket_equals  
- right_angle_bracket_right_angle_bracket_equals  
- caret  
- exclamation_mark  
- exclamation_mark_equals  
- left_angle_bracket  
- right_angle_bracket  
- left_angle_bracket_equals  
- right_angle_bracket_equals  
- left_angle_bracket_left_angle_bracket  
- right_angle_bracket_right_angle_bracket  
- right_angle_bracket_right_angle_bracket_right_angle_bracket  
- right_angle_bracket_right_angle_bracket_right_angle_bracket_equals  
- question_mark  
- interface  
- abstract_class  
- enumeration  
- constant  
- asterisk_forward_slash  
- forward_slash  
- forward_slash_asterisk  
- implements  
- constructor  
- inherits  
- try  
- catch  
- finally  
- tilde  
- is_an_instance_of  


## Examples

### A simple for loop that prints to standard ouput

The for loop syntax is the same as Java and other C-family languages; however, all of the symbols are spelled out.

Printing to the standard output can be done by using the built-in `print` method and then spell out all of the symbols that you would use in a Python print statement, the only difference being the semicolon at the end. 

All statements must end in a `semicolon` in Wordscript 

```
for open_parenthesis integer variable iii equals 0 semicolon iii less_than 10 open_parenthesis void close_parenthesis semicolon iii plus_plus close_parenthesis open_curly_brace 

	print open_parenthesis double_quotation_marks Hello World! double_quotation_marks close_parenthesis semicolon 

close_curly_brace 
```

### A simple class called dog with a constructor, instance variables and methods

Method and constructor overloading are allowed.
Methods are public by default, can be changed to private by adding `private` before the return type of the method.  

Comments are writen after the keyword `forward_slash_forward_slash` as seen in the Dog class below

```
class Dog open_curly_brace 

	
	integer variable age semicolon 

	private string variable name semicolon 


	constructor function open_parenthesis integer age comma string name close_parenthesis open_curly_brace
		
		this dot age equals age semicolon
		
		this dot name equals name semicolon
	
	close_curly_brace


	forward_slash forward_slash Setter Methods
 

	void function setAge open_parethesis integer age close_parenthesis open_curly_brace 

		this dot age equals age semicolon

	close_curly _brace 


	
	forward_slash forward_slash Getter Methods
	
	string function getName open_parenthesis void close_parenthesis open_curly_brace
		
		return name semicolon

	close_curly_brace

	
	forward_slash forward_slash Regular Methods

	void function bark open_parenthesis void close_parenthesis open_curly_brace open_curly_brace
		
		print open_parenthesis double_quotation_marks Woof! double_quotation_marks close_parenthesis semicolon

close_curly_braces
```

#### How to instantiate an object of the dog class

The instantiation of an object is the same as in Java. Again, the only difference is that each of the symbols are spelled out for maximum readability.

```
Dog variable dog equals new dog open_parenthesis integer five comma string double_quotation_marks Fido double_quotation_marks close_parenthesis semicolon
```
