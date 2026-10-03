# Numerical Simulation of Differential Equations

Academic notebooks on diffusion, transport and ecological dynamics, combining model equations with numerical schemes and visualisation.

## Featured studies

| Notebook | Focus |
| --- | --- |
| [Coupled sediment–chemical transport](Project%20sediment_chemical.ipynb) | One-dimensional advection–diffusion–reaction system, inlet/outlet conditions, concentration profiles, parameter comparisons and animation. |
| [Allee-effect dynamics](Assignment_Allee_effect.ipynb) | Prey-only ODE dynamics with an extinction threshold and carrying capacity. |
| [Heat-equation examples](course%201.ipynb) | Homogeneous and forced heat-equation examples and numerical visualisation. |
| [Additional numerical examples](course%202.ipynb) | Time-stepping exercises. |
| [Additional animations](course_3.ipynb) | Differential-equation solution visualisation; some saved cells contain errors. |
| [ODE/PDE tutorial](Tutorial%201%28ODE%20and%20PDE%29%20%282%29.ipynb) | Grid construction and rectangular quadrature methods. |

The sediment–chemical notebook studies coupled concentrations with advection, diffusion, a bilinear reaction term and chemical loss. The Allee-effect notebook currently simulates prey-only dynamics; its title also refers to a broader predator–prey motivation.

## Environment

```bash
python -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter notebook
```

Run notebooks from the repository root. Parameters and initial conditions are defined within the notebooks. GIF creation uses Matplotlib and Pillow.

## Numerical interpretation

Time-step and grid choices, boundary conditions and solver tolerances affect numerical behaviour. The notebooks illustrate the models and methods; a systematic convergence study for the full collection has not yet been recorded.

The published [sediment animation](https://github.com/Thierrykuatemabap/sediment-chemical-animation) is a companion visual asset.

## Academic context

Part of [Thierry Kuate Mabap's computational mathematics portfolio](https://github.com/Thierrykuatemabap). Original notebook content and source references are retained.
