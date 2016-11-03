# 1. The Role of Algorithms in Computing

## 1.1 Algorithms
* 1.1-1. Give a real-world example that requires sorting or a real-world example that requires computing a convex hull.
	* sorting: 스마트폰의 연락처
	* computing a convex hull: ...
* 1.1-2. Other than speed, what other measures of efficiency might one use in a real-world setting?
	* 메모리 효율
* 1.1-3. Select a data structure that you have seen previously, and discuss its strengths and limitations.
	* 배열
		* 장점: 읽기, 쓰기작업시에 어느 인덱스든 한 번에 접근이 가능하다.
		* 단점: 미리 메모리 공간을 할당해야 한다.
* 1.1-4. How are the shortest-path and traveling-salesman problems given above similar? How are they different?
	* similar point: 가장 효율이 좋은 길을 찾아야 한다.
	* different point: traveling-salesman problem은 NP-complete로 더 복잡하고 효율적인 알고리즘은 발견되지 않았다.
* 1.1-5. Come up with real-world problem in which only the best solution will do. Then come up with one in which a solution that is "approximately" the best is good enough.
	* best solution: 간단하게 값을 구할 수 있는 문제. 실생활과 연결하여 떠오르진 않는다.
	* approximately solution: 과정이 복잡하거나 계산하는데 많은 변수가 존재하는 문제. 역시 잘 떠오르지 않는다.

## 1.2 Algorithms as a technology
* 1.2-1. Give an example of an application that requires algorithmic content at the application level, and discuss the function of the algorithms involved.
	* 시뮬레이션 앱
* 1.2-2. Suppose we are comparing implementations of insertion sort and merge sort on the same machine. For input of size n, insertion sort runs in 8n<sup>2</sup> steps, while merge sort run in 64nlgn steps. For which values of n does insertion sort beat merge sort?
	* 8n<sup>2</sup> < 64nlog<sub>2</sub>n
	* n < log<sub>2</sub>n<sup>8</sup>
	* 2<sup>n</sup> < n<sup>8</sup>
	* ...
* 1.2-3. What is the smallest value of n such that an algorithm whose running time is 100n<sup>2</sup> runs faster than an algorithm whose running time is 2<sup>n</sup> on the same machine?
	* 100n<sup>2</sup> < 2<sup>n</sup>
	* ...

## 1. problems
* 1-1. Comparison of running times
For each function f(n) and time t in the following table, determine the largest size n of a problem that can be solved in time t, assuming that the algorithm to solve the problem takes f(n) microseconds.

| | 1 second | 1 minute | 1 hour | 1 day | 1 month | 1 year | 1 century |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| log<sub>2</sub>n |
| log<sub>2</sub>n |
| \sqrt{n} |
| nlog<sub>2</sub>n |
| n<sup>2</sup> |
| n<sup>3</sup> |
| 2<sup>n</sup> |
| n! |
