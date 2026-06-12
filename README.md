# Optimization Exercises

Practice exercises developed as part of the **Continuous and Combinatorial Optimization** course in the UFAL Master's program.

Each notebook formulates a problem with decision variables, constraints, and an objective function, then solves it with [PuLP](https://coin-or.github.io/pulp/) (CBC solver). Notebooks are numbered for reference; `0.` covers a metaheuristic approach outside the linear/integer programming track.

## Exercises


| Notebook                                | Problem                                     |
| --------------------------------------- | ------------------------------------------- |
| `0. Bin Packing - metaheuristica.ipynb` | Bin packing (local search metaheuristic)    |
| `1.racao.ipynb`                         | Feed production (linear programming)        |
| `2.dieta.ipynb`                         | Diet problem (linear programming)           |
| `3.plantio.ipynb`                       | Crop planning (linear programming)          |
| `4.tintas.ipynb`                        | Paint blending (linear programming)         |
| `5.transporte.ipynb`                    | Transportation problem (linear programming) |
| `6.fluxo_max.ipynb`                     | Maximum flow                                |
| `7.escalonamento_horarios.ipynb`        | Nurse scheduling                            |
| `8.cobertura.ipynb`                     | Dominating set / coverage                   |
| `9.mochila.ipynb`                       | Knapsack problem                            |
| `10.clique maxima.ipynb`                | Maximum clique                              |
| `11.padroes.ipynb`                      | Cutting patterns (can production)           |
| `12.facilidades.ipynb`                  | Facility location                           |
| `13.frequencia.ipynb`                   | Frequency assignment                        |
| `14.caixeiro_viajante.ipynb`            | TSP                                         |
| `15.roteamento_veiculos.ipynb`          | CVRP                                        |
| `16.caminho_minimo.ipynb`               | Shortest path                               |


## Requirements

- Python 3.10+
- [PuLP](https://pypi.org/project/PuLP/) — installed automatically in each notebook via `%pip install pulp -q`
- Optional (notebooks `1`, `7`, `13`): `matplotlib`, `pandas`, `networkx`

## Usage

Open any notebook in Jupyter or VS Code and run all cells. The CBC solver runs locally; no API keys are required.

## Team

Juliana Baracho ([jkcm@ic.ufal.br](mailto:jkcm@ic.ufal.br)) and Márcio Oliveira ([mhvo@ic.ufal.br](mailto:mhvo@ic.ufal.br)).