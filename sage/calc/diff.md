type: tutorial
title: Differential
subtitle: This is about the differential
authors:
    Harald Schilly <harald.schilly@univie.ac.at>

# Differentiation

some text here about #differentiation as an #example
and more $x^2$ there.

## Example {: label='example' }

Contains `some code` in backticks as an #Example.

sage::

    ex = 4 * x - x^2
    ex = ((9 - ex)^3).expand()
    show(latex(ex))
    print "differentiated gives:"
    show(latex(ex.diff(x)))
    
    
should give

    ... 
    
This was easy, wasn't it?

And now a link[test/knowl.example|neat link to a knowl example] ... 