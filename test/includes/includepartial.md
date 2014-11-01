title: Partial Includes
subtitle: Test paragraphs for partial includes
seealso:
    includes.includeme

# this is the first part {: label='part1' }

paragraph 1 of part 1

paragraph 2 of part 1

# this is the second part {: label='part2' }

paragraph 1 of part 2  with a $\sum_0^2x_i$ formula and


ASCIIMath of `lim_{y -> \infty} (x-2)^2 / sqrt(y+3) -> 0`
gives ''lim_{y -> \infty} (x-2)^2 / sqrt(y+3) -> 0''

## subheader of part 2

paragraph 1 of part 2/1

python::

    from random import randint
    print "cell test", randint(1, 1e6)

paragraph 2 of part 2/1

# this is the third part {: label='part3' }

paragraph 1 of part 3  and formula:

$$\prod_{\alpha=0}^{\infty} y_{\alpha}^n = 0$$

paragraph 2 of part 3

paragraph 3 of part 3