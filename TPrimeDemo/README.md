[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Juice-jl/JuiceExamples/master?filepath=TPrimeDemo%2FT-Prime-Juice-Demo.ipynb)

## TPrime Demo

Based on notebook presented at [TPrime Social](https://nips.cc/Conferences/2019/Schedule?showEvent=15972) at NeurIPS 2019. Showcasing few usecases of the Juice library.

For easy use, just click on the binder badge above and it would launch the notebook with requirements setup in your browser, thanks to [Binder](https://mybinder.org/).


### Requirements

1. Install [Julia](https://julialang.org/). Version 1.2+.

2. Install [Jupyter](https://jupyter.org). The classic jupyter notebook is enough for our case.

3. Install [IJulia](https://github.com/JuliaLang/IJulia.jl). This adds Julia kernels inside juypter notebooks.

4. Install CSV and Statistics Packages. Run: 

```bash
  julia -e 'using Pkg; Pkg.add("CSV"); Pkg.add("Statistics");' 
```

5. Install Juice packages: Juice packages are not registered yet so follow the installation instructions from [ProbabilisticCircuits.jl](https://github.com/Juice-jl/ProbabilisticCircuits.jl).


### How to run
1. To run a jupyter notebook, first run `jupyter notebook .` in the command line, then a browser tab opens in which you can navigate and open the notebook to run. For more details refer to [this guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).
