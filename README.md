# Applied Probability and Randomized Algorithms
## Description 📌
This repository hosts a series of Interactive Python Notebooks (ipynb files) that cover topics related to applied probabilities and randomized algorithms. It includes simulations of processes, the results of which are compared with what is known from the relevant theory.

Topics covered:
### Balls Into Bins simulations
- **Balls Into Bins**: The balls into bins (or balanced allocations) problem is a classic problem in probability theory that has many applications in computer science. The problem involves $m$ balls and $n$ boxes (or "bins"). Each time, a single ball is placed into one of the bins. [Wikipedia - Balls Into Bins](https://en.wikipedia.org/wiki/Balls_into_bins_problem). This part simulates:
   1. the case where each ball is placed in a randomly selected bin
   2. the case where each ball is placed in the bin with the fewest balls out of two randomly selected bins (partially random allocation)
   3. the heavy loaded case: $m\approx3n*(log_2n)$
      
  For each of these simulations the focus is on comparing the expected value of maximum load both between cases and with the theoretically known results.
  
- **Birthday Paradox**: Assume that $m$ people are in the same room, and we are interested in their birthdays. This is a special case of the balls into bins problem, where we are dealing with the probability of two people sharing the same birthday (= the probability that 2 balls fall in the same bin, where the balls $(m)$ correspond to birthdays and the bins $(n)$ are the days of the year), as well as the expected value of the number of pairs with the same birthday in the room.

- **Coupon Collector**: Again a special case of the balls into bins problem. We have $n=100$ bins (the types of coupons) and an unlimited number of balls (the 'attempts'), which are placed one by one in a randomly selected bin each. The process of successive ball placement in bins stops when all bins contain at least one ball (i.e. the collector has collected all types of coupons).

[Wikipedia - Balls Into Bins](https://en.wikipedia.org/wiki/Balls_into_bins_problem)
### Coin flip simulations
### Die roll simulations
### Poisson Distribution - Poisson Process
### Quicksort - Karger's randomized algorithm
