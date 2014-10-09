title: Testing Includes
subtitle: Testing the include[[ ... ]] statement

Below, there should be the content of link[[includeme]].

include[[includeme]]

## and below again (inline)

start of line include[[includeme]] after the token is here.

cell::

    x = 1
    y = 2*x + 3
    print x, y

EOF
