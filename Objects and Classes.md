<h1>Objects and Classes</h1>

The demo code file is in the same repo with this file: https://github.com/p1geonium/RubySpring2022

<h2>1. Class in Ruby</h2>

a) Defining Class
- A class in Ruby always starts with the keyword ***class*** followed by the name of the class. The name should always be in initial capitals.
- Syntax: 

![image](https://user-images.githubusercontent.com/93970330/163698193-05f12d96-5b82-4ebe-95d6-3a80c2b1ddd7.png)

b) Instance and Class Variables

- **Instance variables** are available across methods for any particular instance or object. That means that instance variables change from object to object. Instance variables are preceded by the **at sign (@)** followed by the variable name.
- **Class variables** are available across different objects. A class variable belongs to the class and is a characteristic of a class. They are preceded by the sign **@@** and are followed by the variable name.

c) Creating Objects using Ruby Class

- Objects are instances of the class, which could be created using method ***new*** of the class. The method ***new*** is a unique type of method, which is predefined in the Ruby library. The ***new*** method belongs to the class methods. Example:

![image](https://user-images.githubusercontent.com/93970330/163698481-b832ed74-cff5-4e6b-94c5-60e478b33ce5.png)

- In order to pass parameters to the method ***new***, a special method called ***initialize*** should be defined. This method would be called if method ***new*** is called with parameters.

![image](https://user-images.githubusercontent.com/93970330/163698695-0a273aee-71f1-4e06-bbb5-35e223749777.png)

d) Member Methods inside Class

- There could be methods defined inside a Class, which could be used to modify class variables, return variables value, or some other purposes. 

![image](https://user-images.githubusercontent.com/93970330/163705855-a62bf2d6-9c88-4810-9202-67d47dbc1128.png)


<h2>2. Inheritance in Ruby</h2>

- Ruby supports only single class inheritance, it does not support multiple class inheritance but it supports ***mixins***. The ***mixins*** are designed to implement multiple inheritances in Ruby, but it only inherits the interface part.

![image](https://user-images.githubusercontent.com/93970330/163706427-bd144ebf-1dd8-4a0f-9800-349af2b00edb.png)

<h2>3. Overloading method in Ruby</h2>

- Ruby *does not* support overloading method. 
- If there are two methods with identical name, the first one will be ignored. Every attempts to call the first method will throw an error. The program will be executed normally if only the second method is called.

![image](https://user-images.githubusercontent.com/93970330/163706463-7ded9421-aa35-480f-9b48-126204a2de21.png)

<h2>Resources</h2>

- Ruby Class and Object: https://www.tutorialspoint.com/ruby/ruby_classes.htm
- Ruby Inheritance: https://www.geeksforgeeks.org/ruby-inheritance/
- Method Overloading in Ruby: https://www.geeksforgeeks.org/method-overloading-in-ruby/
