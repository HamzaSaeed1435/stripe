Answer 1: 
Set TimeOut is an asynchronous function. It means it won't stop execution of other synchronous code. Each Console Log will wait 1 second to execute. But as the value of i has become 100 it will print 100 hundred times.
Why just hundred.


Answer  2: I will wait for setTimout and then promise will resolve and response will print.

Answer 3:  var is function scoped and let and const is blocked scoped. Mainly I recommend let and const. because of block scoped.

Answer 4:  will print [“hello”] and after then  [“hello”,”another”] 


Answer 5 : Exercise Question , its simple i use  stripe ,ejs , express ,bodyparser
