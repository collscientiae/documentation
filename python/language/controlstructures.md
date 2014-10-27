title: Control Structures
subtitle: if/then/else control structures
seealso:
    language.loops
    
# Simple `if` example

python::

    x = 10
    y = 20
    if x > y:
        print "x greater than y"
    else:
        print "x less or equal than y"
        
# If in a Loop

This combines a knowl[language.loops iteration|iteration loop] with an `if`:
 
python::

    ages = [5, 66, 18, 21, 99, 35]
    for age in ages:
        print age, "is",
        if age > 50:
            print "quite old."
        elif age < 10:
            print "pretty young."
        else:
            print "average."
