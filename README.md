# Robertsons Rules for Orderly Plots

This is a starting template for creating plots that follow the general style
for the Computational Astrophysics Research Group.

Nothing here is permanent, but it is a good starting point.

## Setup and Installation

1. To install clone this repository
2. Either run `python install_style.py` or copy the `robertsons_rules.mplstyle`
   manually to user style location
3. In your code, use `plt.style.use("robertsons_rules")`

## Rules

1. Text font should be Helvetica
2. Latex font should be Computer Modern
3. Axes ticks should point in on both the plot and colorbar
4. Legends shoud be frameless
5. Try to avoid Viridis, the default is Magma, but this is not a hard and fast
   rule

