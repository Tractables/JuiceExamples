[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Juice-jl/JuiceExamples/master?filepath=LogicCircuits%2FLogicCircuits.ipynb)


## LogicCircuits Demo

`LogicCircuits` is one of the modules of the Juice library, which in addition to handling logical reasoning tasks, provides the necessary data structures used in the `ProbabilisticCircuits` module. This demo gives code example of its common use cases.

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

5. Install LogicCircuits module. Follow the instructions in the [installation guide](https://juice-jl.githu.b.io/LogicCircuits.jl/dev/installation/)

For more details about jupyter notebooks refer to [this guide](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html).