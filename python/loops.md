type: reference
title: Python Loops
subtitle: Loops are an important control structure
seealso:
    conditionals
    function

something about *python* loops

# For Loop

python::

    for i in range(10):
        print i
        
# While Loop {: label="while"}

python::

    j = 5
    while j >= 0:
        print j
        j -= 1

# Iteration Loop {: label="iteration"}

python::

    who = ["boy", "girl", "teacher", "banana"]
    for name in who:
        print name

python::

    cities = ["peking", "paris", "new york", "casablanca"]
    for index, city in enumerate(cities):
        print index, city