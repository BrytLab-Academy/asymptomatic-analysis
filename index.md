# Asymptomatic Analysis of Algorithms

Asymptomatic analysis of algorithm is refers to the mathematical boundation/framing its runtime performance. Asymptomatic analysis is imput bound. Apart from input all other factors are held contants.

There are three main expressions of asymptomatic analysis namely,Best case scenario, Average case scenario, and Worst Case Scenario.All these three example can be used to express the efficiency of an algorithm but the worst case scenario is the widely used. When the type is not explicitly stated, we always assume the worst case scenario.

Given the list `students`, assuming we are searching for a person and we have to search from the left(*first item*) to the right(*last item*) of the array.

`students = ['Bilson', 'Mansa', 'Kingston', 'John', 'Aminu']`

## Running Times of Algorithm
  - Best Case Scenario\
    This is the maximum amount of time required for a program to run.
    Per the scenario above, we will have the best case scenario when the person of interest is __Bilson__ since it is the first person in the list.

  - Worst Case Scenario\
    This is the maximum amount of time required for a program to run.
    In this case we would have the worst case scenario when we are searching for __Aminu__ because we would have to passs through all the item in the list before we get to __Aminu__.

  - Avarage Case Scenario\
    The avarage time required to run program.
    Searching for __Kingston__ will bw our average case since it is in the middle of the array. This will take half the time to traverse the entire array.

## Asymptomatic Notations
  1. __Ο__ (Big O) Notation
  2. __Ω__ (Omega) Notation
  3. __θ__ (Theta) Notation

All these are valid notation in analysis of algorithm but the Big __O__ Notation is the most widely used.
Below are the some fundamental expressions of the Big __O__ Notation in order of complexity.

### Sample Big __O__ Notations by order of Complexity

| Name        | Big O Notaion     |
| ----------- | ------------      |
| Constant     |   (O)1           |
| Logarithmic  |  O(log n)        |
| Linear       |  O(n)            |
| Log-linear   | O(n log N)       |
| Quadratic    | O(n<sup>2</sup>) |
| Cubic        | O(n<sup>3</sup>) |
| Polynomial   | O(2<sup>n</sup>) |
| Factorial    | O(n!)            |

 ** Note: This is not an exhaustive list of Big O Notatons. 

