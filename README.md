# Coder-Rules

1. Do not repeat yourself (DRY). Write DRY code.
  - Functions can be particularly helpful when it comes to DRY code.
  - Store repeat code into variable to make overall code better looking.

Note: One thing I like about code is that you can make it better and better at your will. You can continue identifying inefficiencies and other ways to make your code cleaner and more maintanable. You can make code look better!

2. Return early.  
   - For example: using "if (!id) return 'No ID provided.';" as your first line ends code right away if '!id' This is sometimes referred to as a GUARD-CLAUSE
   - Guard clause - a statement that evaluates to a boolean that determines whether or not a function should conintue running. Implementing a guard clause in your code will make your code much more efficient and easier to read.

3. Avoid boolean returns when possible.
   - You can avoid boolean returns by returning the expression that is evaluating the statement.  
