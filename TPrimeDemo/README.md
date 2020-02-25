[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Juice-jl/JuiceExamples/master?filepath=TPrimeDemo%2FT-Prime-Juice-Demo.ipynb)

## TPrime Demo

Based on a demo, originally presented at [TPrime Social](https://nips.cc/Conferences/2019/Schedule?showEvent=15972) at NeurIPS 2019. Showcasing few usecases of the Juice library.



### How to run

1. For a quick demo, you can click on the badge on top of this readme to launch a notebook in your browser with the environment. This is thanks to [Binder](https://mybinder.org/).


2. To setup the environment needed to run the notebook locally, follow the instructions below to setup the requirements. Then, run command below to start jupyter. A browser tab opens, navigate to the demo notebook and open it, now it should be ready to run.

  ```bash
  jupyter notebook .
  ```


### Requirements

1. Install [Julia](https://julialang.org/). Version 1.2+.

2. Install [Jupyter](https://jupyter.org). The classic jupyter notebook is enough for our case.

3. Install [IJulia](https://github.com/JuliaLang/IJulia.jl). This adds Julia kernels inside juypter notebooks.

4. Install CSV and Statistics Packages. Run: 

```bash
  julia -e 'using Pkg; Pkg.add("CSV"); Pkg.add("Statistics");' 
```

5. Install Juice packages: Juice packages are not registered yet so follow the installation instructions from [ProbabilisticCircuits.jl](https://github.com/Juice-jl/ProbabilisticCircuits.jl).


For more details about jupyter notebooks refer to [this guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).

