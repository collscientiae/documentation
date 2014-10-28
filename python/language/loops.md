type: reference
title: Loop
subtitle: Loops are an important control structure
seealso:
    language.controlstructures
    language.function
sort: 21
group: Structure

something about *python* loops

# For Loop

The iteration variable `i` is assigned to the list of given values. 

python::

    for i in range(10):
        print i
        
        
It is resilient against modifications during a single iteration:
 
python::

    for k in range(-5,5):
        print "k=", k
        k = k + 2 * k + 1
        print "modified k=", k
        
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

The knowl[language.iterator] `enumerate` knowl[language.iterator yield|yields]
tuples of `(<index number>, element)`.
The `<index number>` knowl[concept.indexing|zero] and increments by `1` for each element
in the knowl[language.list]

    cities = ["peking", "paris", "new york", "casablanca"]
    for index, city in enumerate(cities):
        print index, city
        
## For-else construction

This is useful to iterate until a condition is met.

python::

    for x in [2,5,7,11,15,23,31,97]:
        if x % 3 == 0:
            print x, "is divisible by 3"
            break
    else:
        print "no number was divisible by 3"
        
*Task*: Change the 15 to 17 in the example above and try again.