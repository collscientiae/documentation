title: Testing Includes
subtitle: Testing the include[ ... ] statement
sort: -.5

Below, there should be the content of link[includes.includeme].

include[includes.includeme]

## and below again (inline)

start of line include[includes.includeme] after the token is here.

python::

    x = 1
    y = 2*x + 3
    print x, y

## partial includes

Below, part 2 of link[includes.includepartial] should appear.

include[includes.includepartial part2]

## partial includes with limit

below, you should only see two paragraphs (out of more) of
link[includes.includepartial] part3:

include[includes.includepartial part3 2]

EOF