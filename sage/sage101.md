type: example
title: Sage 101
abstract:
    Some simple explanations about Sage
seealso:
    plotting

The first paragraph starts of with some simple #example text
about the {{ sage }}.

## Complex Example

The second paragraph is a bit more **complex** and _powerful_,
explaining #plotting and more.

example::

    >>> x = var('x')
    >>> diff(x^2/(1-x^3), x)
    3*x^4/(x^3 - 1)^2 - 2*x/(x^3 - 1)

## Another Example

This is another paragraph, below a code without doctest

example::

    >>> (2+3+4)^5
    