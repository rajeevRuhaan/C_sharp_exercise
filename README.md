# This is C Sharp learning repositiory.

### Identifiers:  identifiers are the user-defined name of the program components ###
```script
public class GFG {
    static public void Main () 
    {
          int x;
    }
}
```

*Here the total number of identifiers present in the above example is 3 and the names of these identifiers are:*
- GFG: Name of the class
- Main: Method name
- x: Variable name

#### Rules for defining identifiers in C # :
- The only allowed characters for identifiers are all alphanumeric characters([A-Z], [a-z], [0-9]), ‘_‘
- Identifiers should not contain white spaces.
- Identifiers should not start with digits([0-9]).
- Identifiers are not allowed to use as keywords unless they include @ as a prefix.
- Identifiers do not contain two consecutive underscores in their name because such types of identifiers are used for the implementation.

### C# | Data Types
- Value Data Types :  Ex.: char, integer, short, long, float, double, float, unsigned (uint, ulong, ushort)
- Reference Data Types: exampel: String | Object
- Pointer Data Types: The Pointer Data Types will contain a memory address of the variable value.
  
  ### Syntax:
  ```script
  type* identifier;
  ```
  ### Example:
  ```script
    int* p1, p;   // Valid syntax
    int *p1, *p;   // Invalid 
  ```
### C# | Variables
<h3>Variable is a placeholder of the information which can be changed at runtime. 
And variables allows to Retrieve and Manipulate the stored information.</h3>

*Rules for Naming Variables*
- Variable names can contain the letters ‘a-z’ or ’A-Z’ or digits 0-9 as well as the character ‘_’.
- The name of the variables cannot be started with a digit.
- The name of the variable cannot be any C# keyword say int, float, null, String, etc.
### Example:
```script
int y = 7; // Declaring and initializing the variable at same time
int x; // Declaring variable x
x = 5; // initializing x with value 5
```

### C# | Keywords
*Keywords or Reserved words are the words in a language that are used for some internal process or represent some predefined actions.*

**Keywords in C# is mainly divided into 10 categories as follows:**

1. Value Type Keywords: There are 15 keywords in value types which are used to define various data types.
   
    1 | 2 | 3| 4
    | --- | --- | --- | --- |
    bool | bytes | char | decimal
    double | enum |float | int
    long | sbyte | short | struct 
    unit | ulong  | ushort

2. Reference Type Keywords: There are 6 keywords in reference types which are used to store references of the data or objects. 
    The keywords in this category are: class, delegate, interface, object, string, void.
 

1. Modifiers Keywords: There are 17 keywords in modifiers which are used to modify the declarations of type member.

    1 | 2 | 3 | 4
    | --- | --- | --- | --- |
    public | private | internal | protected	
    abstract | const | event | extern	
    new	| override | partial | readonly	
    sealed | static	| unsafe | virtual	
    volatile	