title: Testing Includes
subtitle: Testing the include[[ ... ]] statement

Below, there should be the content of link[[includeme]].

include[[includeme]]

## and below again (inline)

start of line include[[includeme]] after the token is here.

python::

    x = 1
    y = 2*x + 3
    print x, y

## partial includes

Below, part 2 of link[[includepartial]] should appear.

include[[includepartial part2]]

## partial includes with limit

below, you should only see two paragraphs (out of more) of link[[includepartial]] part3:

include[[includepartial part3 2]]

EOF