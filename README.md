# Smallest Enclosing Circle Algorithms

<div align="center">
<img src="https://i.imgur.com/LEatCcm.png" width="65px" height='65px'/>
</div>

![ipython](https://img.shields.io/badge/ipython-7.16.1-blue)
![matplotlib](https://img.shields.io/badge/matplotlib-3.2.2-blue)
![numpy](https://img.shields.io/badge/numpy-1.18.5-blue)
![Apache License 2.0](https://img.shields.io/badge/license-Apache%20License%202.0-blue)

## Table of Contents

- [Smallest Enclosing Circle Algorithms](#smallest-enclosing-circle-algorithms)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Naive Algorithm](#naive-algorithm)
  - [Welzl Algorithm](#welzl-algorithm)
  - [Comparison](#comparison)
  - [Conclusion](#conclusion)
  - [References](#references)
  - [Additional Notes] (#additional-notes)

## Introduction

This IPython Notebook demonstrates the implementation and comparison of two algorithms for finding the smallest enclosing circle for a set of points: the Naive algorithm and the Welzl algorithm.
The Welzl algorithm is an improvement over the naive algorithm, which has a worst-case time complexity of O(n<sup>4</sup>).

## Naive Algorithm

The naive algorithm for finding the smallest enclosing circle for a set of points is to find all possible circles that contain two or three points, and then find the smallest circle among them. The naive algorithm is simple to implement, but it is inefficient. The naive algorithm has a worst-case time complexity of O(n<sup>4</sup>).

The following code implements the naive algorithm for finding the smallest enclosing circle for a set of points. The code is based on the pseudocode provided in the [Wikipedia article](https://en.wikipedia.org/wiki/Smallest-circle_problem#Naive_algorithm).

## Welzl Algorithm

The Welzl algorithm is an efficient randomized algorithm for finding the smallest enclosing circle for a set of points. The Welzl algorithm is based on the idea of recursive elimination. The algorithm starts with an empty circle, and then adds points to the circle one by one. At each step, the algorithm checks if the circle contains all the points. If the circle does not contain all the points, then the algorithm adds a point to the circle and checks again. If the circle contains all the points, then the algorithm stops. The algorithm is guaranteed to find the smallest enclosing circle for a set of points.

The following code implements the Welzl algorithm for finding the smallest enclosing circle for a set of points. The code is based on the pseudocode provided in the [Wikipedia article](https://en.wikipedia.org/wiki/Smallest-circle_problem#Welzl's_algorithm).

## Comparison

The following code compares the performance of the naive algorithm and the Welzl algorithm for finding the smallest enclosing circle for a set of points. The code generates a set of points and then runs the naive algorithm and the Welzl algorithm on the set of points. The code then plots the results.

The following figure shows the results of running the naive algorithm and the Welzl algorithm on a set of points. The figure shows that the Welzl algorithm is much faster than the naive algorithm.

## Additional Notes

> The implementation of the Naive algorithm is provided as a reference, but it may not be efficient for large datasets. The Welzl algorithm is recommended for practical use.

> Feel free to modify the code or extend the notebook to suit your specific requirements.

## Conclusion

The Welzl algorithm is an efficient randomized algorithm for finding the smallest enclosing circle for a set of points. The Welzl algorithm is based on the idea of recursive elimination. The algorithm starts with an empty circle, and then adds points to the circle one by one. At each step, the algorithm checks if the circle contains all the points. If the circle does not contain all the points, then the algorithm adds a point to the circle and checks again. If the circle contains all the points, then the algorithm stops. The algorithm is guaranteed to find the smallest enclosing circle for a set of points.

## References

- [Smallest-circle problem](https://en.wikipedia.org/wiki/Smallest-circle_problem)
- [ Welzl's algorithm](https://www.nayuki.io/page/smallest-enclosing-circle)
