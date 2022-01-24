PythonBasics_1

In the below elements which of them are values or an expression? eg:- values can be integer or string and expressions will be mathematical operators. '*', 'hello', -87.8,-, /, +, 6

What is the difference between string and variable?

Describe three different data types.

What is an expression made up of? What do all expressions do?

This assignment statements, like spam = 10. What is the difference between an expression and a statement?

After running the following code, what does the variable bacon contain? bacon = 22 bacon + 1

What should the values of the following two terms be? 'spam' + 'spamspam' 'spam' * 3

Why is eggs a valid variable name while 100 is invalid?

What three functions can be used to get the integer, floating-point number, or string version of a value?

Why does this expression cause an error? How can you fix it? 'I have eaten ' + 99 + ' burritos.'

PythonBasics_2

1.What are the two values of the Boolean data type? How do you write them? 2. What are the three different types of Boolean operators? 3. Make a list of each Boolean operator's truth tables (i.e. every possible combination of Boolean values for the operator and what it evaluate ). 4. What are the values of the following expressions? (5 > 4) and (3 == 5) not (5 > 4) (5 > 4) or (3 == 5) not ((5 > 4) or (3 == 5)) (True and True) and (True == False) (not False) or (not True) 5. What are the six comparison operators? 6. How do you tell the difference between the equal to and assignment operators?Describe a condition and when you would use one. 7. Identify the three blocks in this code: spam = 0 if spam == 10: print('eggs') if spam > 5: print('bacon') else: print('ham') print('spam') print('spam') 8. Write code that prints Hello if 1 is stored in spam, prints Howdy if 2 is stored in spam, and prints Greetings! if anything else is stored in spam. 9.If your programme is stuck in an endless loop, what keys you’ll press? 10. How can you tell the difference between break and continue? 11. In a for loop, what is the difference between range(10), range(0, 10), and range(0, 10, 1)? 12. Write a short program that prints the numbers 1 to 10 using a for loop. Then write an equivalent program that prints the numbers 1 to 10 using a while loop. 13. If you had a function named bacon() inside a module named spam, how would you call it after importing spam?

PythonBasics_3

Why are functions advantageous to have in your programs?
When does the code in a function run: when it's specified or when it's called?
What statement creates a function?
What is the difference between a function and a function call?
How many global scopes are there in a Python program? How many local scopes?
What happens to variables in a local scope when the function call returns?
What is the concept of a return value? Is it possible to have a return value in an expression?
If a function does not have a return statement, what is the return value of a call to that function?
How do you make a function variable refer to the global variable?
What is the data type of None?
What does the sentence import areallyourpetsnamederic do?
If you had a bacon() feature in a spam module, what would you call it after importing spam?
What can you do to save a programme from crashing if it encounters an error?
What is the purpose of the try clause? What is the purpose of the except clause?
PythonBasics_4

What exactly is []?
In a list of values stored in a variable called spam, how would you assign the value 'hello' as the third value? (Assume [2, 4, 6, 8, 10] are in spam.) Let's pretend the spam includes the list ['a', 'b', 'c', 'd'] for the next three queries.
What is the value of spam[int(int('3' * 2) / 11)]?
What is the value of spam[-1]?
What is the value of spam[:2]? Let's pretend bacon has the list [3.14, 'cat,' 11, 'cat,' True] for the next three questions.
What is the value of bacon.index('cat')?
How does bacon.append(99) change the look of the list value in bacon?
How does bacon.remove('cat') change the look of the list in bacon?
What are the list concatenation and list replication operators?
What is difference between the list methods append() and insert()?
What are the two methods for removing items from a list?
Describe how list values and string values are identical.
What's the difference between tuples and lists?
How do you type a tuple value that only contains the integer 42?
How do you get a list value's tuple form? How do you get a tuple value's list form?
Variables that "contain" list values are not necessarily lists themselves. Instead, what do they contain?
How do you distinguish between copy.copy() and copy.deepcopy()?
PythonBasics_5

What does an empty dictionary's code look like?

What is the value of a dictionary value with the key 'foo' and the value 42?

What is the most significant distinction between a dictionary and a list?

What happens if you try to access spam['foo'] if spam is {'bar': 100}?

If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys()?

If a dictionary is stored in spam, what is the difference between the expressions 'cat' in spam and 'cat' in spam.values()?

What is a shortcut for the following code? if 'color' not in spam: spam['color'] = 'black'

How do you "pretty print" dictionary values using which module and function?

PythonBasics_6

What are escape characters, and how do you use them?

What do the escape characters n and t stand for?

What is the way to include backslash characters in a string?

The string "Howl's Moving Castle" is a correct value. Why isn't the single quote character in the word Howl's not escaped a problem?

How do you write a string of newlines if you don't want to use the n character?

What are the values of the given expressions? 'Hello, world!'[1] 'Hello, world!'[0:5] 'Hello, world!'[:5] 'Hello, world!'[3:]

What are the values of the following expressions? 'Hello'.upper() 'Hello'.upper().isupper() 'Hello'.upper().lower()

What are the values of the following expressions? 'Remember, remember, the fifth of July.'.split() '-'.join('There can only one.'.split())

What are the methods for right-justifying, left-justifying, and centering a string?

What is the best way to remove whitespace characters from the start or end?

PythonBasics_7

What is the name of the feature responsible for generating Regex objects?
Why do raw strings often appear in Regex objects?
What is the return value of the search() method?
From a Match item, how do you get the actual strings that match the pattern?
In the regex which created from the r'(\d\d\d)-(\d\d\d-\d\d\d\d)', what does group zero cover? Group 2? Group 1?
In standard expression syntax, parentheses and intervals have distinct meanings. How can you tell a regex that you want it to fit real parentheses and periods?
The findall() method returns a string list or a list of string tuples. What causes it to return one of the two options?
In standard expressions, what does the | character mean?
In regular expressions, what does the character stand for? 10.In regular expressions, what is the difference between the + and * characters?
What is the difference between {4} and {4,5} in regular expression?
What do you mean by the \d, \w, and \s shorthand character classes signify in regular expressions?
What do means by \D, \W, and \S shorthand character classes signify in regular expressions?
What is the difference between .? and .?
What is the syntax for matching both numbers and lowercase letters with a character class?
What is the procedure for making a normal expression in regax case insensitive?
What does the . character normally match? What does it match if re.DOTALL is passed as 2nd argument in re.compile()?
If numReg = re.compile(r'\d+'), what will numRegex.sub('X', '11 drummers, 10 pipers, five rings, 4 hen') return?
What does passing re.VERBOSE as the 2nd argument to re.compile() allow to do?
How would you write a regex that match a number with comma for every three digits? It must match the given following: '42' '1,234' '6,368,745'
but not the following: '12,34,567' (which has only two digits between the commas) '1234' (which lacks commas) 21. How would you write a regex that matches the full name of someone whose last name is Watanabe? You can assume that the first name that comes before it will always be one word that begins with a capital letter. The regex must match the following: 'Haruto Watanabe' 'Alice Watanabe' 'RoboCop Watanabe' but not the following: 'haruto Watanabe' (where the first name is not capitalized) 'Mr. Watanabe' (where the preceding word has a nonletter character) 'Watanabe' (which has no first name) 'Haruto watanabe' (where Watanabe is not capitalized) 22. How would you write a regex that matches a sentence where the first word is either Alice, Bob, or Carol; the second word is either eats, pets, or throws; the third word is apples, cats, or baseballs; and the sentence ends with a period? This regex should be case-insensitive. It must match the following: 'Alice eats apples.' 'Bob pets cats.' 'Carol throws baseballs.' 'Alice throws Apples.' 'BOB EATS CATS.' but not the following: 'RoboCop eats apples.' 'ALICE THROWS FOOTBALLS.' 'Carol eats 7 cats.'

PythonBasics_8

Is the Python Standard Library included with PyInputPlus?
Why is PyInputPlus commonly imported with import pyinputplus as pypi?
How do you distinguish between inputInt() and inputFloat()?
Using PyInputPlus, how do you ensure that the user enters a whole number between 0 and 99?
What is transferred to the keyword arguments allowRegexes and blockRegexes?
If a blank input is entered three times, what does inputStr(limit=3) do?
If blank input is entered three times, what does inputStr(limit=3, default='hello') do?
PythonBasics_9

To what does a relative path refer?
What does an absolute path start with your operating system?
What do the functions os.getcwd() and os.chdir() do?
What are the . and .. folders?
In C:\bacon\eggs\spam.txt, which part is the dir name, and which part is the base name?
What are the three “mode” arguments that can be passed to the open() function?
What happens if an existing file is opened in write mode?
How do you tell the difference between read() and readlines()?
What data structure does a shelf value resemble?
PythonBasics_10

How do you distinguish between shutil.copy() and shutil.copytree()?
What function is used to rename files??
What is the difference between the delete functions in the send2trash and shutil modules? 4.ZipFile objects have a close() method just like File objects’ close() method. What ZipFile method is equivalent to File objects’ open() method?
Create a programme that searches a folder tree for files with a certain file extension (such as .pdf or .jpg). Copy these files from whatever location they are in to a new folder.
PythonBasics_11

Create an assert statement that throws an AssertionError if the variable spam is a negative integer.
Write an assert statement that triggers an AssertionError if the variables eggs and bacon contain strings that are the same as each other, even if their cases are different (that is, 'hello' and 'hello' are considered the same, and 'goodbye' and 'GOODbye' are also considered the same).
Create an assert statement that throws an AssertionError every time.
What are the two lines that must be present in your software in order to call logging.debug()?
What are the two lines that your program must have in order to have logging.debug() send a logging message to a file named programLog.txt?
What are the five levels of logging?
What line of code would you add to your software to disable all logging messages? 8.Why is using logging messages better than using print() to display the same message?
What are the differences between the Step Over, Step In, and Step Out buttons in the debugger? 10.After you click Continue, when will the debugger stop ?
What is the concept of a breakpoint?
PythonBasics_12

In what modes should the PdfFileReader() and PdfFileWriter() File objects will be opened?
From a PdfFileReader object, how do you get a Page object for page 5?
What PdfFileReader variable stores the number of pages in the PDF document?
If a PdfFileReader object’s PDF is encrypted with the password swordfish, what must you do before you can obtain Page objects from it?
What methods do you use to rotate a page?
What is the difference between a Run object and a Paragraph object?
How do you obtain a list of Paragraph objects for a Document object that’s stored in a variable named doc?
What type of object has bold, underline, italic, strike, and outline variables?
What is the difference between False, True, and None for the bold variable?
How do you create a Document object for a new Word document?
How do you add a paragraph with the text 'Hello, there!' to a Document object stored in a variable named doc?
What integers represent the levels of headings available in Word documents?
PythonBasics_13

What advantages do Excel spreadsheets have over CSV spreadsheets? 2.What do you pass to csv.reader() and csv.writer() to create reader and writer objects?
What modes do File objects for reader and writer objects need to be opened in?
What method takes a list argument and writes it to a CSV file?
What do the keyword arguments delimiter and line terminator do?
What function takes a string of JSON data and returns a Python data structure?
What function takes a Python data structure and returns a string of JSON data?
PythonBasics_14

What does RGBA stand for?
From the Pillow module, how do you get the RGBA value of any images?
What is a box tuple, and how does it work?
Use your image and load in notebook then, How can you find out the width and height of an Image object?
What method would you call to get Image object for a 100×100 image, excluding the lower-left quarter of it?
After making changes to an Image object, how could you save it as an image file?
What module contains Pillow’s shape-drawing code?
Image objects do not have drawing methods. What kind of object does? How do you get this kind of object?
PythonBasics_15

1.How many seconds are in an hour? Use the interactive interpreter as a calculator and multiply the number of seconds in a minute (60) by the number of minutes in an hour (also 60). sol. 60 2. Assign the result from the previous task (seconds in an hour) to a variable called seconds_per_hour. 3. How many seconds do you think there are in a day? Make use of the variables seconds per hour and minutes per hour. 4. Calculate seconds per day again, but this time save the result in a variable called seconds_per_day 5. Divide seconds_per_day by seconds_per_hour. Use floating-point (/) division. 6. Divide seconds_per_day by seconds_per_hour, using integer (//) division. Did this number agree with the floating-point value from the previous question, aside from the final .0? 7. Write a generator, genPrimes, that returns the sequence of prime numbers on successive calls to its next() method: 2, 3, 5, 7, 11, ...

PythonBasics_16

Create a list called years_list, starting with the year of your birth, and each year thereafter until the year of your fifth birthday. For example, if you were born in 1980. the list would be years_list = [1980, 1981, 1982, 1983, 1984, 1985].
In which year in years_list was your third birthday? Remember, you were 0 years of age for your first year. 3.In the years list, which year were you the oldest?
Make a list called things with these three strings as elements: "mozzarella", "cinderella", "salmonella".
Capitalize the element in things that refers to a person and then print the list. Did it change the element in the list?
Make a surprise list with the elements "Groucho," "Chico," and "Harpo."
Lowercase the last element of the surprise list, reverse it, and then capitalize it.
Make an English-to-French dictionary called e2f and print it. Here are your starter words: dog is chien, cat is chat, and walrus is morse.
Write the French word for walrus in your three-word dictionary e2f.
Make a French-to-English dictionary called f2e from e2f. Use the items method.
Print the English version of the French word chien using f2e.
Make and print a set of English words from the keys in e2f.
Make a multilevel dictionary called life. Use these strings for the topmost keys: 'animals', 'plants', and 'other'. Make the 'animals' key refer to another dictionary with the keys 'cats', 'octopi', and 'emus'. Make the 'cats' key refer to a list of strings with the values 'Henri', 'Grumpy', and 'Lucy'. Make all the other keys refer to empty dictionaries.
Print the top-level keys of life.
Print the keys for life['animals'].
Print the values for life['animals']['cats']
PythonBasic_17

Assign the value 7 to the variable guess_me. Then, write the conditional tests (if, else, and elif) to print the string 'too low' if guess_me is less than 7, 'too high' if greater than 7, and 'just right' if equal to 7.
Assign the value 7 to the variable guess_me and the value 1 to the variable start. Write a while loop that compares start with guess_me. Print too low if start is less than guess me. If start equals guess_me, print 'found it!' and exit the loop. If start is greater than guess_me, print 'oops' and exit the loop. Increment start at the end of the loop.
Print the following values of the list [3, 2, 1, 0] using a for loop.
Use a list comprehension to make a list of the even numbers in range(10)
Use a dictionary comprehension to create the dictionary squares. Use range(10) to return the keys, and use the square of each key as its value.
Construct the set odd from the odd numbers in the range using a set comprehension (10).
Use a generator comprehension to return the string 'Got ' and a number for the numbers in range(10). Iterate through this by using a for loop.
Define a function called good that returns the list ['Harry', 'Ron', 'Hermione'].
Define a generator function called get_odds that returns the odd numbers from range(10). Use a for loop to find and print the third value returned.
Define an exception called OopsException. Raise this exception to see what happens. Then write the code to catch this exception and print 'Caught an oops'.
Use zip() to make a dictionary called movies that pairs these lists: titles = ['Creature of Habit', 'Crewel Fate'] and plots = ['A nun turns into a monster', 'A haunted yarn shop'].
PythonBasics_18

Create a zoo.py file first. Define the hours() function, which prints the string 'Open 9-5 daily'. Then, use the interactive interpreter to import the zoo module and call its hours() function.
In the interactive interpreter, import the zoo module as menagerie and call its hours() function.
Using the interpreter, explicitly import and call the hours() function from zoo.
Import the hours() function as info and call it.
Create a plain dictionary with the key-value pairs 'a': 1, 'b': 2, and 'c': 3, and print it out. 6.Make an OrderedDict called fancy from the same pairs listed in 5 and print it. Did it print in the same order as plain?
Make a default dictionary called dict_of_lists and pass it the argument list. Make the list dict_of_lists['a'] and append the value 'something for a' to it in one assignment. Print dict_of_lists['a'].
PythonBasics_19

Make a class called Thing with no contents and print it. Then, create an object called example from this class and also print it. Are the printed values the same or different?
Create a new class called Thing2 and add the value 'abc' to the letters class attribute. Letters should be printed.
Make yet another class called, of course, Thing3. This time, assign the value 'xyz' to an instance (object) attribute called letters. Print letters. Do you need to make an object from the class to do this?
Create an Element class with the instance attributes name, symbol, and number. Create a class object with the values 'Hydrogen,' 'H,' and 1.
Make a dictionary with these keys and values: 'name': 'Hydrogen', 'symbol': 'H', 'number': 1. Then, create an object called hydrogen from class Element using this dictionary.
For the Element class, define a method called dump() that prints the values of the object’s attributes (name, symbol, and number). Create the hydrogen object from this new definition and use dump() to print its attributes.
Call print(hydrogen). In the definition of Element, change the name of method dump to str, create a new hydrogen object, and call print(hydrogen) again.
Modify Element to make the attributes name, symbol, and number private. Define a getter property for each to return its value.
Define three classes: Bear, Rabbit, and Octothorpe. For each, define only one method: eats(). This should return 'berries' (Bear), 'clover' (Rabbit), or 'campers' (Octothorpe). Create one object from each and print what it eats.
Define these classes: Laser, Claw, and SmartPhone. Each has only one method: does(). This returns 'disintegrate' (Laser), 'crush' (Claw), or 'ring' (SmartPhone). Then, define the class Robot that has one instance (object) of each of these. Define a does() method for the Robot that prints what its component objects do.
PythonBasics_20

Set the variable test1 to the string 'This is a test of the emergency text system,' and save test1 to a file named test.txt.
Read the contents of the file test.txt into the variable test2. Is there a difference between test 1 and test 2?
Create a CSV file called books.csv by using these lines: title,author,year The Weirdstone of Brisingamen,Alan Garner,1960 Perdido Street Station,China Miéville,2000 Thud!,Terry Pratchett,2005 The Spellman Files,Lisa Lutz,2007 Small Gods,Terry Pratchett,1992
Use the sqlite3 module to create a SQLite database called books.db, and a table called books with these fields: title (text), author (text), and year (integer).
Read books.csv and insert its data into the book table.
Select and print the title column from the book table in alphabetical order.
From the book table, select and print all columns in the order of publication.
Use the sqlalchemy module to connect to the sqlite3 database books.db that you just made in exercise 6.
Install the Redis server and the Python redis library (pip install redis) on your computer. Create a Redis hash called test with the fields count (1) and name ('Fester Bestertester'). Print all the fields for test.
Increment the count field of test and print it.
PythonBasics_21

Add the current date to the text file today.txt as a string.
Read the text file today.txt into the string today_string
Parse the date from today_string.
List the files in your current directory
Create a list of all of the files in your parent directory (minimum five files should be available).
Use multiprocessing to create three separate processes. Make each one wait a random number of seconds between one and five, print the current time, and then exit.
Create a date object of your day of birth.
What day of the week was your day of birth?
When will you be (or when were you) 10,000 days old?
PythonBasics_22

What is the result of the code, and explain?
>>> X = 'iNeuron' >>> def func(): print(X)

>>> func()

What is the result of the code, and explain?
>>> X = 'iNeuron' >>> def func(): X = 'NI!'

>>> func() >>> print(X)

What does this code print, and why?
>>> X = 'iNeuron' >>> def func(): X = 'NI' print(X)

>>> func() >>> print(X)

What output does this code produce? Why?
>>> X = 'iNeuron' >>> def func(): global X X = 'NI'

>>> func() >>> print(X)

What about this code—what’s the output, and why?
>>> X = 'iNeuron' >>> def func(): X = 'NI' def nested(): print(X) nested()

>>> func() >>> X

How about this code: what is its output in Python 3, and explain?
>>> def func(): X = 'NI' def nested(): nonlocal X X = 'Spam' nested() print(X)

>>> func()

PythonBasics_23

What is the result of the code, and why? >>> def func(a, b=6, c=8): print(a, b, c) >>> func(1, 2)
What is the result of this code, and why? >>> def func(a, b, c=5): print(a, b, c) >>> func(1, c=3, b=2)
How about this code: what is its result, and why? >>> def func(a, *pargs): print(a, pargs) >>> func(1, 2, 3)
What does this code print, and why? >>> def func(a, **kargs): print(a, kargs) >>> func(a=1, c=3, b=2)
What gets printed by this, and explain? >>> def func(a, b, c=8, d=5): print(a, b, c, d) >>> func(1, *(5, 6))
what is the result of this, and explain? >>> def func(a, b, c): a = 2; b[0] = 'x'; c['a'] = 'y' >>> l=1; m=[1]; n={'a':0} >>> func(l, m, n)
>>> l, m, n

PythonBasics_24

What is the relationship between def statements and lambda expressions ?
What is the benefit of lambda?
Compare and contrast map, filter, and reduce.
What are function annotations, and how are they used?
What are recursive functions, and how are they used?
What are some general design guidelines for coding functions?
Name three or more ways that functions can communicate results to a caller.
PythonBasics_25

. What is the difference between enclosing a list comprehension in square brackets and parentheses?
What is the relationship between generators and iterators?
What are the signs that a function is a generator function?
What is the purpose of a yield statement?
What is the relationship between map calls and list comprehensions? Make a comparison and contrast between the two.
