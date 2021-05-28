# EPAI3--Session_4

### Numeric Types-II
##### The following concepts were covered:

- Decimals
- Decimal Operations
- Decimal Performance
- Complex Numbers
- Booleans
- Boolean Precedence
- Comparison Operators

## ***ASSIGNMENT***

To write a Qualean class that is inspired from Boolean + Quantum concepts.

It can take only three possible real states - True , False or Maybe [1,0,-1].

The moment you assign it a real number, it immediately finds an imaginary number random.uniform(-1, 1) and multiplies with it and stores that number internally after using Bankers rounding to 10th decimal place.

It implements these functions (with exactly the same names):

__ and__ ,  __ or __ , __ repr__ , __ str__ , __ add__ , __ eq__ , __ float__ , __ ge__ , __ gt__ , __ invertsign__ , __ le__ , __ lt__ , __ mul__ , __ sqrt__ , __ bool__

The task was to write the above class and all the function.

## *Code*:
The following functions:

- __ init __:  the init function either takes the user's input or sets to default = ''. Checks if the user's input is valid else raises a ValueError(). If no user's input then a random choice is made from [-1,0,1]. This is then multipied with a random number in the range [-1,1].The result is then rounded of to 10th decimal place using the Banker's rounding algorithm.



- return_qualean(): Returns the qualean number.

- __ bool __ : Returns the bool value of qualean number. True if there exists a qualean number else False.

- __ repr __ : This returns the object representation.

- __ str __ : Returns the string representation of qualean class.

- __ invertsign __: Function returns the inverted value.

- __ sqrt __: Function returns the square_root value. for negative number it returns the square root of its positive number along with 'i' == sqrt(-1).

- __ float__: Function returns the float value

- __ and __: Performs the "and" function. Logic of "and" is return x if x is False else y.

- __ or __: Performs the "or" function. Logic of "or" is return x if x is True else y

- __ add __: Performs addition function. If the type of second argument is invalid it raises a TypeError.

- __ mul __: Performs multiplication function. If the type of second argument is invalid it raises a TypeError.

- the following functions performs the standard operation
  -  __ ge __ as greater than or equal to
  -  __ gt __ as greater than
  -  __ le __ as less than or equal to
  -  __ lt __ as less than
  -  __ eq __ as equal to


## *Test_ Cases*

The test_session4.py file totally consists of 42 test cases.

1. "***test_ readme_exists***": Checks if README.md exists.

2. "***test_ readme_contents***": Checks if README.md has atleast 500 words.

3. "***test_ readme_ proper_description***": Checks if README.md has the words specified in README _ CONTENT _ CHECK _FOR[] list.
4. "***test_ readme_ file_ for_formatting***": Checks if README.md has atleast 10 '#'.

5. "***test_indentations***" Returns pass if used four spaces for each level of syntactically significant indenting.

6. "***test_ function_ name_ had_ cap_letter***": Checks if any function name has capital letters.

7. "***test _ qualean _ repr***": Checks if __ repr __ funtion returns a proper description.

8. "***test_ qualean_ str***": Checks if __ str __ funtion returns a proper string representation.

9. "***test_ function_ qualean_ type***": Checks the type of qualean object.

10. "***test_ qualean_ decimal_ precision***" Checks if qualean class is rounding of to the 10th decimal place. 

11. "***test_ function_ count***": Checks if test_session4.py file has test cases more than 25.

12. "***test_ function_ repeatations***": Checks if there are any repeated test cases in test-session4.py

13. "***test_ 100_ qualeans***": Test case for 100 times sum of Qualean.

14. "***test_ function_ sqrt***": Test case for __ sqrt __ method.

15. "***test_ million_ qualeans_ sum***": Test case for MILLION Qualeans addition.

16. "***test_ million_ qualeans_ mul***":Test case for MILLION Qualeans multiplication.

17. "***test_ qualean_ valid_ input***": Raises an ValueError if user enters a invalid input.

18. "***test_ invalid_ input_ valueerror_ provides_ relevant_ message***": Checks for revelant ValueError message when input is invalid.

19. "***test_ qualean_ validity***": Checks if qualean class creates a valid Qualean.

20. "***test_ function_ and***": Checks the "and" operation of two qualeans.

21. "***test_ and_ q_ notdefined***": Checks the "and" operation of a qualean and a non-qualean.

22. "***test_ and_ q_ false***": Checks the "and" operation when First Qualean is False.

23. "***test_ function_ or***":Checks the "or" operation of two qualeans.

24. "***test_ or_ q_ notdefined***": Checks the "or" operation of a qualean and a non-qualean.

25. "***test_ or_ q_ false***": Checks the "or" operation when First Qualean is True.

26. "***test_ function_ add***": Checks the __ add __ method.

27. "***test_ function_ add_ non_ qualean***": Checks the __ add __ method when second argument is non-qualean.

28. "***test_ function_ mul***": Checks the __ mul __ method.

29. "***test_ function_ mul_ non_ qualean***": Checks the __ mul __ method when second argument is non-qualean.

30. "***test_ function_ ge***": Checks the __ ge __ method.

31. "***test_ function_ ge_ non_ qualean***": Checks the __ ge __ method when second argument is non-qualean.

32. "***test_ function_ gt***": Checks the __ gt __ method.

33. "***test_ function_ gt_ non_ qualean***": Checks the __ gt __ method when second argument is non-qualean.

34. "***test_ function_ le***": Checks the __ le __ method.

35. "***test_ function_ le_ non_ qualean***": Checks the __ le __ method when second argument is non-qualean.

36. "***test_ function_ lt***": Checks the __ lt __ method.

37. "***test_ function_ lt_ non_ qualean***": Checks the __ lt __ method when second argument is non-qualean.

38. "***test_ function_ with_ non_ number***": Checks if __ add __ , __ mul __ , __ eq __, __ ge __, __ gt __, __ le __, __ lt __ raises an TypeError when an invalid argument such as strings are passed.

39. "***test_ function_ bool***": Checks the __ bool __ method.

40. "***test_ function_ eq***": Checks the __ eq __ method.

41. "***test_ function_ float***": Checks the __ float __ method.

42. "***test_ function_ invertsign***" Checks the __ invertsign __ method.