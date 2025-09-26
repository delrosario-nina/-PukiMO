# PokeDSL
[!PokeMO]
**Creator**
Del Rosario, Nina Claudia E.
Hernia, Christian Joseph G.


**Language Overview**
PUKIMO is a dynamically typed scripting language inspired by the game Pokemon GO, designed for creating, managing, and interacting with Pokemon and trainers. 
Main Characteristics

- Close to english language
- Arrow-based method chaining (->) 
- Static/class-level access (::) for queries and utilities
- Focused on catching, managing, and inspecting Pokemon


**Keywords**
Trainer : Defines a trainer object
catch : Trainer method to catch Pokemon
release : Trainer method to release Pokemon
team : Trainer method to view Pokemon team
Pokemon : Define a Pokemon object
info : Pokemon method to view Pokemon info
all : Static/Class method to egt all instances of the object
find : Static/Class method to find Pokemin or trainers by name
shiny : Boolean with only true or flase values
fainted : Boolean with only true or flase values
while : While loop
else : else
flee : ends loop
trycatch : For loop for Pokemon


**Operators**
Arithmetic Operators
+ 
-
/
*
%

Comparison Operators
<
>
==
!=
<=
>=

Logical Operators
AND 
OR
NOT

Assignment Operators
=

**Literals**
Numbers: Only integers are supported (decimal points are not allowed).
Example: 42, 100, 1234
Strings: Enclosed in double quotes " ".
Example: "Pikachu", "Ash"
Shiny / Fainted: Boolean values to keep Pokémon flavor.
shiny → true
fainted → false
Null: none represents a null value (like null or nil).
Array: Enclosed in square brackets [ ].

**Identifiers**
Definition: Names used for variables, functions (move), and objects (Trainer, Pokemon).
Rules for valid identifiers:
Must start with a letter (A-Z or a-z) or an underscore (_).
Can contain letters, digits (0-9), and underscores (_).
Cannot be a reserved keyword (like catch, pokeball, trycatch, shiny, etc.).
Case sensitivity: Identifiers are case-sensitive.
Example: Ash and ash are treated as different identifiers.


**Comments**
// Comments are written like this
// Multi-line comments are written like this 
   Nested comments are not supported //



**Syntax Style**
Whitespace is not significant, but indentation will be used for organization and readability.
Statements end on a newline, adding a semicolon is optional. 
Blocks use curly braces ‘{ }’ for grouping
Instance method chaining will use ‘->’  (e.g., Ash -> catch(Pokemon))
Static/Class calls will use ‘: :’ (e.g.,Pokemon : : all)

**Sample Code**
[Provide a few examples of valid code in your language to demonstrate the syntax and features]


**Design Rationale**
[Explain the reasoning behind your design choices]
