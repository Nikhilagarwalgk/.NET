1. Go to project directory:
    - Compilation -> dotnet build
    - Run ur project -> dotnet run

2. Initializing a new string:-
   ```
           string[] fraudulentOrderIDs = new string[3];

            fraudulentOrderIDs[0] = "A123";
            fraudulentOrderIDs[1] = "B456";
            fraudulentOrderIDs[2] = "C789"; 
     ```
3. Looping through an array using foreach
```
    string[] names = { "Rowena", "Robin", "Bao" };
    foreach (string name in names)
    {
        Console.WriteLine(name);
    }
```
4. Variable name rules:
   - Variable names can contain alphanumeric characters and the underscore (_) character. Special characters like the pound         #, the dash -, and the dollar sign $ are not allowed.
   - Variable names must begin with an alphabetical letter or an underscore, not a number. Using an underscore character          to start a variable name is typically reserved for private instance fields. A link to further reading can be found           in the module summary.
   - Variable names should use camel case
   ```
       string thisIsCamelCase;
       char userOption;
       int gameScore;
       float particlesPerMillion;
       bool processedCustomer;
   ```









