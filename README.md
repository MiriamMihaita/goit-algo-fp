# goit-algo-fp
# Monte Carlo Simulation of Dice Sums

## Introduction

This project involved simulating a large number of dice throws using the Monte Carlo method to calculate the probability of each possible sum (from 2 to 12) and comparing these results with the analytical probabilities.

## Results

The Monte Carlo simulation was run for 1,000,000 dice throws. The probabilities calculated from the simulation closely matched the analytical probabilities, with minor differences due to the stochastic nature of the simulation.

| Sum | Monte Carlo Probability | Analytical Probability |
|-----|--------------------------|------------------------|
| 2   | 2.78%                    | 2.78%                  |
| 3   | 5.57%                    | 5.56%                  |
| 4   | 8.34%                    | 8.33%                  |
| 5   | 11.13%                   | 11.11%                 |
| 6   | 13.88%                   | 13.89%                 |
| 7   | 16.66%                   | 16.67%                 |
| 8   | 13.90%                   | 13.89%                 |
| 9   | 11.10%                   | 11.11%                 |
| 10  | 8.32%                    | 8.33%                  |
| 11  | 5.54%                    | 5.56%                  |
| 12  | 2.78%                    | 2.78%                  |

## Conclusion

The Monte Carlo simulation provided results that closely aligned with the theoretical probabilities, demonstrating the effectiveness of the Monte Carlo method for probabilistic simulations. Differences observed are attributed to the random nature of the simulation and would likely decrease with an even larger number of simulations.
