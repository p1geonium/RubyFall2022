<h1>Names, Types and Binding</h1>


<h2>1. Data Types</h2>

There are (at least) 6 data types in Ruby: Numbers, Boolean, Strings, Hashes, Arrays, and Symbols.

**Numbers** is the data type used to hanlde both interger and floating point numbers.
  
 - Example: 
 
   random_float = 0.00001337420069
 
   random_cal = 9/random_float         #result will be a float number, not being auto rounded.


**Boolean** is the data type used to represent 1 bit of information: true or false. Everything in Ruby is truthy except the two values *false* and *nil*.

- Example:

  if true
    
    puts "Result is true"
    
  elif nil
  
    puts "Result is false"
    
  else
    
    puts "Result is false"

**String** is the data type used to represent a series of characters or letters, defined with a pair of the character ['] or ["] at the beginning and the ending.

- Example:
  
  hello = "Hello, world!"
  puts hello
  
**Hash** is the data type that assign its values to its key with the operation [=>]. The key pairs is separated with a comma between them and all the pairs are enclosed within curly braces. A Hash could be considered similar to Python Dictionary.

- Example:
  
  cars = {"car1" => "ferrari", "car2" => "bently", "car3" => "lamborghini"}
  
**Array** is the data type used to store data or list of data. Array can contain all type of data. Data in an array are separated by comma in between them and are enclosed within square bracket.The index of elements in an array starts with 0.

- Example:
  
  array = [ "pigeon", 17, 12.02, [0 ,2 ,4], "last element"]
  
**Symbol** is the data type that quite similar to String, but require less memory space. A symbol is preceded by a colon (:).

- Example: (symbols used as key in a hash)

  cars = {:c1 => "ferrari", :c2 => "toyota"}
  
  
<h2>2. Naming Convention</h2>

There is not any official naming convention for Ruby. The following rules were mainly developed by the developer community.

- Identifiers should be named with English.
- Identifiers do not start with a number.
- Use CapitalCase for naming identifier of Class and Module, which means that use capital letter for every first characters of the words and do not include underscores among words (GuitarHero, HelloWorld,...)
- Use SnakeCase for naming Symbols, Methods, Variables, Files Name, and Directory, which means that use lower case letters at every position and include underscores among words and numbers (hello_world.rb, hello_world(), mil_nare, int_ball_1,...)
- Use ScreamingSnakeCase for naming Constants, which means that use SnakeCase with all captial letters.

<h2>3. Reserved words/keywords in Ruby</h2>

The reserved words/keywords could not be used for naming identifiers.
  
![image](https://user-images.githubusercontent.com/93970330/156921081-8a47abf5-b2dc-4ebc-9c05-b12d4b875f74.png)

<h2>4. Discussion</h2>

- Ruby is a dynamic language, which means that the lines of codes are checked in the run time.
- Ruby is strongly typed, which means that typing errors are checked/reported at run time.
- Ruby allows both explicitly and implicitly typed.

<h2>Resources</h2>

Ruby data types: https://www.geeksforgeeks.org/ruby-data-types/
Ruby style guide: https://github.com/rubocop/ruby-style-guide
Ruby typing: https://blog.heroku.com/static-typing-ruby-with-sorbet

  
  
