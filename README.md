<div id="header" align="center">
    <img alt="Stars and Moon" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMjJ3NHR6aTV0MG52MXIzMW54M3dmZGl5NDAwaWZubjZvb3Rxa2djMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/c03rO2ssTRxVneP3Yg/giphy.gif" height="150"">
</div>

# Applied Probability and Randomized Algorithms
## Description 📌
This repository hosts a series of Interactive Python Notebooks (ipynb files) that cover topics related to applied probabilities and randomized algorithms. It includes simulations of processes, the results of which are compared with what is known from the relevant theory.

## Topics covered 🔎
### Coin flip simulations
- **A single fair coin**: This part deals with the Bernoulli distribution and the Binomial distribution as well as with basic concepts of probability theory (conditional probabilities, independence etc.)

- **Two coins; One fair and one biased**: In this part the focus is on applying the Law of Total Probability and the Bayes Theorem
  
### Die roll simulations
- **Fair die roll simulations**: This part provides a simulation of a Discrete Random Variable that takes more than two values through another Random Variable that follows the Uniform(0,1) distribution. The focus is on the notions of independence, expected value and conditional expected value.
  
- **Geometric distribution using coin flip simulations**: This part simulates the Geometric distribution and estimates various probabilities, expected values etc.
  
- **Law of Large Numbers (LLN) using a fair coin**: The Law of Large Numbers highlights that as we increase the number of samples (iterations) in an experiment, the sample mean approaches the expected value. This part aim to experimentally confirm the validity of the LLN and visualize the relevant results through graphs.
  
### Poisson Distribution - Poisson Process
- **Poisson Distribution**: This part studies the accuracy of approximating the Binomial distribution with an expected value of 1 (i.e., $p = 1/N$) by the Poisson distribution with an expected value of $\lambda = 1$.
  
- **Poisson Process simulation**: This part simulates the "generation" of points based on the Poisson process with a rate of $λ$ points per unit of time and estimates various probabilities, expected values etc which are compared with the theoretically predicted ones. Additionally, as part of the poisson process simulation, this part includes the implementation of the well known Inverse Transform Method, which serves for simulating a Continuous Random Variable through another Random Variable that follows the Uniform(0,1) distribution (in this case, the Exponential distribution is simulated using the Uniform(0,1)).

### Quicksort - Karger's randomized algorithm
- **Quicksort**: Quicksort is an efficient, general-purpose sorting algorithm that exploits the divide-and-conquer technique [Read More](https://en.wikipedia.org/wiki/Quicksort). This part provides a randomized implementation of the algorithm (where the pivot element is randomly picked) and compares the theoretically known complexity results with the experimentally observed ones.
  
- **Karger's Algorithm**: Karger's algorithm is a randomized algorithm to compute a minimum cut of a connected graph. [Read more](https://en.wikipedia.org/wiki/Karger%27s_algorithm). This part provides an implementation of this algorithm and deals with the generally applied idea of "probability amplification". Again, the theoretically known results are compared with the experimentally observed ones.

### Balls Into Bins simulations
- **Balls Into Bins**: The balls into bins (or balanced allocations) problem is a classic problem in probability theory that has many applications in computer science. The problem involves $m$ balls and $n$ boxes (or "bins"). Each time, a single ball is placed into one of the bins. [Wikipedia - Balls Into Bins](https://en.wikipedia.org/wiki/Balls_into_bins_problem). This part simulates:
   1. the case where each ball is placed in a randomly selected bin
   2. the case where each ball is placed in the bin with the fewest balls out of two randomly selected bins (partially random allocation)
   3. the heavy loaded case: $m\approx3n*(log_2n)$
      
  For each of these simulations the focus is on comparing the expected value of maximum load both between cases and with the theoretically known results.
  
- **Birthday Paradox**: Assume that $m$ people are in the same room, and we are interested in their birthdays. This is a special case of the balls into bins problem, where we are dealing with the probability of two people sharing the same birthday (= the probability that 2 balls fall in the same bin, where the balls $(m)$ correspond to birthdays and the bins $(n)$ are the days of the year), as well as the expected value of the number of pairs with the same birthday in the room.

- **Coupon Collector**: Again a special case of the balls into bins problem. We have $n=100$ bins (the types of coupons) and an unlimited number of balls (the 'attempts'), which are placed one by one in a randomly selected bin each. The process of successive ball placement in bins stops when all bins contain at least one ball (i.e. the collector has collected all types of coupons).

## Contributor
- Alviona Mancho [<a href="https://github.com/alvionaM">alvionaM</a>]
