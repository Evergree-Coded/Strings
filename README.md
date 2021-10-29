## Strings ##

### What are Strings? ###

Strings are objects containing a sequence of characters surrounded by double quotes

Ex: `"My name is Nick"`

Ex: `"I like to go walking"`

String are immutable, which means that you can't chage them after they've been constructed. However, you can always take parts of a string for a New String.



### Constructing String Objects ###
We can create string objects similar to primitive data types.

`String name = "Nick";`

Explanation: A variable called name is declared with the identifier object String and initialized with the value "Nick"

### Concatenation of Strings ###
Strings can be added together using an operator called concatenation. With concatentation you can produce a single string given two or more strings.

Example:

`String firstName = "Nick";`

`String lastName = "A";`

`String fullName = firstName + " " + lastName;`


Example:

`String id = "Age";`

`int num = 5;`

What does this output:
`String age =  5;`?

You cannot assign integer data types to strings!


### Comparing Strings ###
You can compare Strings in Java using two different methods.
- `equals()` method
- `compareTo()` method

For the equals() method:

`string1.equals(string2);`, this returns a boolean value, either true if the two strings are equal, or false otherwise.

Example:

`String name1 = "Dog";`

`String name2 = "Cat";`

`System.out.println(name1.equals(name2));` results in false

`String name3 = "Dog";`

`System.out.println(name1.equals(name3));` results in true


For the compareTo() method:

`string1.compareTo(string2);`

- Returns 0 if the two strings are equal
- Returns a value greater than 0 if the first string precedes the second string in the dictionary
- Returns a value less than 0 if the second string precedes the first string in the dictionary

Example:

`name1.compareTo(name2);` returns a value less than 0.
Why?

`name1.compareTo(name3);` returns 0


### Indexing Strings ###
Even though strings are immutable, you are able to take parts of a string to use for a new string.

Method: substring()

The substring() method has two different forms:

- The first form takes a single integer input and returns the characters of the string from the index of the input to the end.

Example:

`String dinosaur = "Triceratops";`

`String half = dinosaur.substring(5);` half results to "ratops"

Keep in mind that with this method the 5 is inclusive, meaning the substring includes the character that the index is referring to.

- The second form takes two integer inputs and returns the characters of the string from the first integer input to the character before the second integer input.

Example:

`String dinosaur = "Triceratops";`

`String half = dinosaur.substring(2, 5);` half results to "ice"

### Other String Methods ###

There are other string methods that are useful for you!!

String Length:

To find the length of a string, you can use the method length(). This method returns the length of the string as an integer.

Example:

`String name = "Nicholas";`

`int length = name.length();` returns the integer value 8.




