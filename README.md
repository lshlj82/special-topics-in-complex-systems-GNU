# Special Topics in Complex Systems: Interactive Demos

Landing page for the interactive web demos that accompany *Special Topics in Complex Systems*, a graduate course in the Department of Physics, Gyeongsang National University.

**Live page:** https://lshlj82.github.io/special-topics-in-complex-systems-GNU/

**Repository:** https://github.com/lshlj82/special-topics-in-complex-systems-GNU

Created by Claude Opus 5.5, based on the lecture notes by Prof. Sang Hoon Lee.

## Demos

| # | Demo | Links |
|---|------|-------|
| 1 | Percolation on the Bethe lattice | [demo](https://lshlj82.github.io/percolation-Bethe/) · [source](https://github.com/lshlj82/percolation-Bethe) |
| 2 | Percolation on the 2D square lattice | [demo](https://lshlj82.github.io/percolation-2D/) · [source](https://github.com/lshlj82/percolation-2D) |
| 3 | Percolation on networks | [demo](https://lshlj82.github.io/percolation-on-networks/) · [source](https://github.com/lshlj82/percolation-on-networks) |
| 4 | The Ising model: introduction | [demo](https://lshlj82.github.io/Ising-model-preliminary/) · [source](https://github.com/lshlj82/Ising-model-preliminary) |
| 5 | The 1D Ising model | [demo](https://lshlj82.github.io/Ising-model-1D/) · [source](https://github.com/lshlj82/Ising-model-1D) |
| 6 | Mean-field and Landau theory of the Ising model | [demo](https://lshlj82.github.io/Ising-model-MF-Landau/) · [source](https://github.com/lshlj82/Ising-model-MF-Landau) |
| 7 | The 2D Ising model | [demo](https://lshlj82.github.io/Ising-model-2D/) · [source](https://github.com/lshlj82/Ising-model-2D) |
| 8 | The renormalization group for the Ising model | [demo](https://lshlj82.github.io/Ising-model-RG/) · [source](https://github.com/lshlj82/Ising-model-RG) |

## About the page

The page is a single self-contained `index.html` with no build step. Its header animates block-spin renormalization of the 2D Ising model. Three Metropolis simulations on 128 × 128 lattices run below, at, and above the critical temperature, and each is coarse-grained three times by 2 × 2 majority-rule block spins (ties keep the top-left spin). Below *T*<sub>c</sub> the configurations flow toward order, above *T*<sub>c</sub> toward uncorrelated noise, and at *T*<sub>c</sub> they look statistically the same at every scale.

The page supports light and dark mode and adapts to phone screens. For visitors who have reduced motion turned on, it shows a still frame instead of the animation.

## Running locally

Open `index.html` in any modern browser. Fonts load from Google Fonts when online and fall back to system fonts otherwise.

## Deploying

1. Put `index.html` and this `README.md` at the root of the repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The page will be served at `https://lshlj82.github.io/<repository-name>/`.

## References

- Kim Christensen and Nicholas R. Moloney, *Complexity and Criticality* (Imperial College Press, 2005).
- Prof. Sang Hoon Lee, lecture notes for Special Topics in Complex Systems.
