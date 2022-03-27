<h1>PLP 3-Selection Control Structures</h1>
  
<h2>1. Boolean value</h2>
  
A ***boolean*** is a value used in a logic statement to say if something is considered true or false.
  
There are two boolean values in Ruby: ***true*** and ***false***
  
In a boolean context, or logical expression, everything is considered ***true*** except the two value:

    - false
    - nil
    
These two value are the **ONLY** values considered falsy.

<h2>2. Conditional statements</h2>

- Ruby allows many types of conditional statements, including **if..else**, **unless**, and **case**.
- Code blocks under each condition in selection control statements are delimited by using the same line indent, normally double space characters compared to their statement.

a) Ruby **if...else** Statement.

- Executes code if the *conditional* is ***true***. If the *conditional* is not ***true***, code specified in the else clause is executed.
- An if expression's *conditional* is separated from code by the reserved word ***then***, a *newline*, or a *semicolon*.
- Syntax:

    if conditional [then]
  
      code...  
    [elsif conditional [then]
  
      code...]...    
    [else
  
      code...]   
    end

b) Ruby **unless** Statement.

- Executes code if *conditional* is ***false***. If the *conditional* is ***true***, code specified in the **else** clause is executed.
- Syntax:

  unless conditional [then]
  
      code...
    
  [else
  
      code  ]
   
  end
  
c) Ruby **case** Statement.

- Compares the expression specified by case and that specified by when using the === operator and executes the code of the when clause that matches.
- The expression specified by the when clause is evaluated as the left operand. If no when clauses match, case executes the code of the else clause.
- A when statement's expression is separated from code by the reserved word then, a newline, or a semicolon.
- Syntax:

  case expression
  
  [when expression [, expression ...] [then]
  
      code ]...
  [else
  
      code ]
      
  end

<h2>3. Ruby short-circuit evaluation</h2>

- Ruby **ALLOWS** short-circuit evaluation: it evaluates the first argument to decide if it should continue with the second one.
- The expression used in short-circuit evaluation are: *and*, *or*, *&&*, and *||*.

<h2>3. Dangling else in Ruby</h2>

- The dangling else is a problem in programming of parser generators in which an optional else clause in an if–then(–else) statement results in nested conditionals being ambiguous. Formally, the reference context-free grammar of the language is ambiguous, meaning there is more than one correct parse tree.
- Example: 

    if a then if b then s else s2
    
    => Two ways of interpret:
    
    if a then (if b then s) else s2
    
    if a then (if b then s else s2)
    
- This problem could be fixed by cover the conditional block with a pair of bracket, as mentioned in the example above, or switch into multi-line conditional.

<h2>4. break, next statement in Ruby</h2>

- The **break** statement could be used to escape loop in Ruby, but it will not work with ***case***.
- Similarly, **next** could be used to skip loop iteration, but it could not be used for evaluating all conditions in ***case***.

<h2>Resources</h2>

- Ruby conditional statements: https://www.tutorialspoint.com/ruby/ruby_if_else.htm
- Ruby boolean values: https://www.rubyguides.com/2019/02/ruby-booleans/
- Ruby short-circuit evaluation: https://mixandgo.com/learn/ruby/boolean-operator-precedence
- Wikipedia's dangling else definition: https://en.wikipedia.org/wiki/Dangling_else
- Ruby *break* and *next* statement: https://www.geeksforgeeks.org/ruby-break-and-next-statement/
