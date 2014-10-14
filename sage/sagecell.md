type: example
title: SageCell
abstract:
    Embedded interactive code-cells
seealso:
    sage101

The following is a quick demo for [SageCells](https://sagecell.sagemath.org/static/about.html).

sage::

    @interact
    def example1(k = slider(0, 10, 0.1, default= 3)):
        expr = sin(k * pi * x) / exp(k * x^2)
        latex(expr)
        p = plot(expr, (x, -5, 5))
        p.show()
        
Drag the slider!

There are no knowl[test/formulas].

