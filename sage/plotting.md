title: 2D Plotting
subtitle: plotting in two dimensions
type: tutorial

A #plot showing how to #[plot plot a plot].

sage::

    x = var('x')
    y = 21+x
    z = 6 * y + x
    plot(x * sin(x+y+z), (x, -10, 10))
