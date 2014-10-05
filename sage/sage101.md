type: example
title: A very simple example
abstract:
    Some text explaining what's going on
seealso:
    plotting

# Simple Example

The first paragraph starts of with some simple #example text
about {{ sage }}.

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
    