1. The bug in the code is that num1 and num2 are retrieved from the HTML elements as strings, not as numbers. When we use the + operator with strings, it concatenates them instead of adding them mathematically.

2. To fix this, we can convert num1 and num2 to numbers before performing addition.  
