1. For data console in C# (C- sharp) we have:- Console.WriteLine("Hello World");
 ; is important in this language

2. C# is a case-sensitive language, meaning that the C# compiler considers the words console and Console as different as the words cat and dog.

3. Always use " ", no ' '. As single quotes is allowed for char datatype. When the phrase is surrounded by double-quotation marks in your C# code, it's called a literal string. 

4. Console.WriteLine("hello") -> Print the next console data **in next line**.
   Console.Write("hello") -> Print the next console in the **same line.**

5. How C# works?
   ->  compiler converts your source code into a different format that the computer's central processing unit (CPU) can execute. The code you wrote was **first compiled, then executed**.

6. The Console part is called a **class**. **Classes "own" methods**; or you could say that methods live inside of a class. There's also a dot (or period) that separates the class name Console and the method name WriteLine(). The period is the **member access operator**. In other words, the dot is how you "navigate" from the class to one of its methods.

7. The WriteLine() part is called a method. The parentheses after the method's name. The parentheses are known as the method invocation operator.

8.  The **semicolon** is the end of statement operator. A statement is a complete instruction in C#. The semicolon tells the compiler that you've finished entering the command.

9. There are different literal data types in C#:-
    1. char -> For a single alphanumeric character, surrounded by a **single quotes**. The term char is short for character.                In C#, this data type is officially named "char", but frequently referred to as a "character".
                eg:- Console.WriteLine('b');
       Note:- double quotation marks creates a string data type.
       
    2. int ->  In C#, this data type is officially named "int", but frequently referred to as "integer".
               eg:- Console.WriteLine(123);

    3. float -> A floating-point number is a number that contains a decimal, for example 3.14159. C# supports three data                     types to represent decimal numbers: float, double, and decimal. Each type supports varying **degrees of                        precision**.
                                Float Type    Precision
                               ----------------------------
                               float         ~6-9 digits,
                               double        ~15-17 digits,
                               decimal        28-29 digits,
    
    4. We can add literal in any number to denote its datattype;-
       1. float - > Console.WriteLine(0.35f); OR Console.WriteLine(0.25F);
       2. double -> With no literal, the compiler takes it to default as double
       3. decimal - > Console.WriteLine(0.34m); OR Console.WriteLine(0.34M);
      
    5.  bool literal - > representing either true or false, often referred as "Boolean".
       
    6.  The main takeaway is that there are many data types, but you'll focus on just a few for now:

           - string for words, phrases, or any alphanumeric data for presentation, not calculation
           - char for a single alphanumeric character
           - int for a whole number
           - decimal for a number with a fractional component
           - bool for a true/false value

  7. An implicitly typed local variable is created by using the var keyword followed by a variable initialization. For example:
     var msg = "hello";
     it must be assigned a value while initialization.

  8.  **Escape character sequence**  is an instruction to the runtime to insert a special character that will affect the output of            your string. In C#, the escape character sequence begins with a backslash \ followed by the character you're escaping The \n          sequence will add a new line, and a \t sequence will add a tab.
  9.  1. Use character escape sequences when you need to insert a special character into a literal string, like a tab \t, new line              \n, or a double quotation mark \".
      2. Use an escape character for the backslash \\ when you need to use a backslash in all other scenarios.
      3.Use the @ directive to create a verbatim string literal that keeps all whitespace formatting and backslash characters in a            string.
      4. Use the \u plus a four-character code to represent Unicode characters (UTF-16) in a string.
      5. Unicode characters may not print correctly depending on the application.


  











