<h1>Loops and Subroutines</h1>

The demo codes could be found in the same GitHub repo as this file: https://github.com/p1geonium/RubySpring2022

<h2>1. Loops in Ruby</h2>

a) **while** Loop

- Syntax of **while** loop in Ruby:

![image](https://user-images.githubusercontent.com/93970330/162554717-0323f755-418a-4aec-8927-0a49735c2ccb.png)

- When the *conditional* is **true**, the code inside the while loop will be executed repeatly. When the *conditional* is false, the loop stops.
- A while loop’s conditional is separated from code by the reserved word do, a newline, backslash(\), or a semicolon(;).

b) **for** Loop

- Syntax of **for** loop in Ruby:

![image](https://user-images.githubusercontent.com/93970330/162554764-22bf1559-07a7-4e32-a155-010690dd1d21.png)

- The codes inside a **for** loop are executed repeatly over a specified range of numbers by the range operator or an array variable.

c) **do..while** Loop

- Syntax of **do..while** loop in Ruby:

![image](https://user-images.githubusercontent.com/93970330/162555000-97401c90-20d7-4764-b651-4f8b65eaf816.png)

- **do..while** loop is similar to while loop with the only difference that it checks the condition after executing the statements, which means that the codes inside **do..while** loop will be executed at least 1 time.

d) **until** Loop

- Syntax of **until** loop in Ruby:

![image](https://user-images.githubusercontent.com/93970330/162555027-04019886-67a6-403c-971e-a0a72cc34f2b.png)

- Ruby's **until** loop is oposite to the **while** loop: it executes the statements or code till the given condition evaluates to true.

<h2>2. Methods in Ruby</h2>

- In Ruby, **Method** is a collection of statements that perform some specific task and return the result. They are defined with the keyword **def** followed by name of the method and ends with **end** keyword. The syntax of method is:

Without parameter:

![image](https://user-images.githubusercontent.com/93970330/162556522-6140a7fe-318b-42c7-a630-9a302625e5da.png)

With parameters:

![image](https://user-images.githubusercontent.com/93970330/162556532-80c88bba-bd21-48a7-a2af-93a90319dc5c.png)

- **RULE**: A method must be defined **before calling** and the name of the method should be in lowercase. Methods are simply called by its name.

<h2>3. return statement and Recursion</h2>

a) **return** statement.
- **return** statement is placed inside a function to returns one or more values, which are always objects.
- To return multiple values at the same time, the variables/values returned are seperated by a comma ("***,***"). For example: return value1, value2, value3.
- The returned values will become an array of values when assigned to a single variable.

b) Recursion in Ruby
- Ruby does support recursion method.

<h2>4. Pass-by-value/reference</h2>
- Ruby is a pass-by-value programming language, but the value it passes are references so that the function and caller reference to the same object in the memory through different variables.

<h2>Resource</h2>

Ruby's Loops: https://www.geeksforgeeks.org/ruby-loops-for-while-do-while-until/

Ruby's Methods: https://www.geeksforgeeks.org/ruby-methods/?ref=lbp

Recursion in Ruby: https://www.geeksforgeeks.org/recursion-in-ruby/

Is Ruby pass-by-value or pass-by-reference: https://robertheaton.com/2014/07/22/is-ruby-pass-by-reference-or-pass-by-value/
