Happy that you landed on my GitHub page!

I'm an environmental engineer who pivoted into scientific Python programming for data science with a main focus on signal processing and statistics. Since I'm short in time, you will not find big repositories with many stars. My contributions are more niche and can be found in bug fixes, issue reports, and forum posts.

# Selected Contributions

- [`pybandee`](https://github.com/MothNik/pybandee/tree/refactor-penta-numba) is a `numba`-implementation of the [`pentapy`](https://github.com/GeoStat-Framework/pentapy)-backend for solving pentadiagonal linear systems. I also implemented the multi-threading for `pentapy` in `Cython` (see [this pending PR](https://github.com/GeoStat-Framework/pentapy/pull/27)), but I needed a `numba`-compatible solutions, so I implemented my own.
- A cubic spline interpolator for [`PyLops`](https://github.com/PyLops/pylops). Its implementation can be used within `pytorch` and allows for backpropagation in case one needs to constrain the output of an optimization or deep learning model to be smooth without introducing explicit constraints or penalties.
- A signal envelope estimation presented in [this StackExchange answer](https://dsp.stackexchange.com/a/94829/72391).
- An example on how to find outliers that mask each other in linear regression using `scipy` in [this StackOverflow answer](https://stackoverflow.com/a/77251627/14814813). The insights I gained here are now also part of the [Wikipedia article on Cook's distance](https://en.wikipedia.org/wiki/Cook%27s_distance#Relationship_to_other_influence_measures_(and_interpretation)).
