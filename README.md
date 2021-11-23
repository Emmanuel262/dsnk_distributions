# dsnk-distributions package

dsnk distribution is a Python module for data science and machine learning that was created with the goal of reducing calculation complexity.

## Files

- **Gaussian distribution** for calculating and visualizing a Gaussian distribution. calculation and representation of mean value, and standard deviation of the distribution. Output a histogram of the instance variable data using matplotlib pyplot library.

* **Binomial distribution** for calculating and visualizing a Binomial distribution. Inherit functionality from Gaussian distribution with addition of represnting probability of an event occuring n (int) number of trials.

* **Generic distribution** class for calculating and visualizing a probability distribution. It performs its functions with help of Binomial distribution and Gaussian distribution.



## User installation

The easiest way to install dsnk_distribution is using pip

```
    pip install dsnk_distribution
```

or conda:

```
    conda install dsnk_distribution
```

###### access classes and functions
```
from dsnk_distributions import Gaussian, Binomial
```

**or**:
```
from dsnk_distributions import Gaussian
from dsnk_distributions import Binomial
```

###### Source code

You can check the latest sources with the command:

```
git clone https://github.com/Emmanuel262/dnsk_distribution.git
```

## Development

The project began after learning the fundamentals of data science and machine learning, and volunteers will soon be needed to help enhance the project's performance and efficiency, as the tasks to be improved will be posted soon.
