title: SageCell Tests
abstract: testing various modes and the functionality of such a
        sage cell
      
## Python Mode (block has an empty line)

python::

    x = 2
    y = 2*x + 5
    print x, y, x*y    
    
    z = x + y
    print "z = %s" % z

which should print `2 9 18` and `z = 4`.

knowl[sage/knowl.interact|interactive mode]:

python::

    @interact
    def _(x = slider(-10, 10, .1, 5),
          y = slider(-10, 10, .1, 5)):
        z = 2*x + 5*y + 1
        print x, y, z, x*y*z

## Sage Mode

sage::

    P.<x> = PolynomialRing(GF(2), 1)
    print [P.random_element(5) for _ in range(10)]
    

## No specific mode, embedded in the text

This line must stay here!

    a = 1
    b = 2
    c = 3
    print a, b, c

Above the previous block must be "This line must stay here!"

## some R code

r::

    zz <- c(1,4,3,4,3,2,3,2,3,2)
    summary(zz)

EOF