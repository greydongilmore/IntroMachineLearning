## Chapter 2: Supervised Learning

# 2.1 Learning a Class from examples
* Class learning is finding a description that is shared by all the positive examples and nine of the negative examples
  * Price and engine power seperate family car from all others
  * Price and engine power are inputs to class recognizer
* Let's deonte *x*<sub>1</sub> as price and *x*<sub>2</sub> as engine power
  * Each car represented by two numeric values: 
<p align="center"><img src="http://latex.codecogs.com/gif.latex?\mathbf{x}&space;=&space;\begin{bmatrix}&space;\textsl{x}_{1}\\&space;\textsl{x}_{2}&space;\end{bmatrix}&space;\right&space;]"></a>
  
* It's label denotes its type:
<p align="center"><img src="http://latex.codecogs.com/gif.latex?r&space;=&space;\begin{Bmatrix}&space;1\;&space;if\;&space;\mathrm{x}\;&space;is\;&space;a\;&space;positive\;&space;example\\&space;0\;&space;if\;&space;\mathrm{x}\;&space;is\;&space;a\;&space;negative\;&space;example&space;\end{matrix}"></a>

* each car is represented by an ordered pair (__*x*__,r), training set contains N examples
<p align="center"><img src="http://latex.codecogs.com/gif.latex?\boldsymbol{X}&space;=&space;\left&space;\{&space;\boldsymbol{x}^{t},r^{t}&space;\right&space;\}_{t=1}^{N}"></a>

* t indexes different examples in the set
