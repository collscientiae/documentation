type: reference
title: Loop
subtitle: Loops are an important control structure
seealso:
    language.controlstructures
    language.function

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
        print name.title()

python::

The knowl[language.iterator] `enumerate` knowl[language.iterator yield|yields]
tuples of `(<index number>, element)`.
The `<index number>` knowl[concept.zero_based_indexing|zero] and increments by `1` for each element
in the knowl[language.list]

    cities = ["peking", "paris", "new york", "casablanca"]
    for index, city in enumerate(cities):
        print index, city
        
