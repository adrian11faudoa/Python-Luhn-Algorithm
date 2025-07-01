Subject:

Python comes with built-in classes that can help us with string manipulation. 
One of them is the str class. It has a method called maketrans that can help us create a translation table. 
This table can be used to replace characters in a string.

Example Code:
        str.maketrans({'t': 'c', 'l': 'b'})

The translate method must be called on the string to be translated with the translation table as an argument:

Example Code:
        my_string = "tamperlot"
        translation_table = str.maketrans({'t': 'c', 'l': 'b'})
        translated_string = my_string.translate(translation_table)


You can also use the index operator to access a range of characters in a string with string[start:stop:step]:

Example Code:
        my_string = 'camperbot'
        my_string[0:6] == 'camper' # True
        my_string[0:6:3] == 'cp' # True

Just as the step is optional, a start at 0 and an end at the end of the slice are optional:

Example Code:
        my_string = 'camperbot'
        camperbot = my_string[::]

Integer division results in the quotient of the division, rounded down to the nearest integer.

Example Code:
        my_number = 12
        first_digit = my_number // 10
        second_digit = my_number % 10

