# Genetic algorithm

## Simple optimization

You are the owner of two regions with employees, each of which produces useful metals: aluminum and nickel. Your task is to obtain the largest amount of alloy of these two metals, with limited resources in people and time. A genetic algorithm can be used to solve this optimization problem. This task will be solved both with the help of its own implementation of the genetic algorithm, and with the help of the implementation of this algorithm in the PyGAD library. Note that this problem is taken from the final math exam for high school students.

![factories](resources/factories.jpg)

[View IPython Notebook](https://github.com/Omazz/genetic-algorithm/blob/main/simple_optimization.ipynb?create=1)

## PID controller
Suppose you need to set up a PID controller for a temperature sensor. As a rule, such a task is solved manually by sorting through all possible coefficients. However, if you use a genetic algorithm, you can find the necessary coefficients for the PID controller without your own intervention.
To do this, you will need to select a loss function, the minimum of which the genetic algorithm will try to achieve in the situation described by us.
In our case, this will be the root of the root mean square error (RMSE). The PyGAD library will be used as an implementation of the genetic algorithm.

![temperature_sensor](resources/temperature_sensor.jpg)

[View IPython Notebook](https://github.com/Omazz/genetic-algorithm/blob/main/pid_controller.ipynb?create=1)

P.S.:
All images are taken from the [freepik](https://www.freepik.com/) website.