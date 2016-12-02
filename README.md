# idea-chelper
Forked from the work of Egor Kulikov, An amaziong toolkit help me a lot. Really Appreciate.

Personaly, I just want to add some Checker classes related to "Precision/Recall" presentations, which can be useful in Machine Learning
Area. But those can also be used in "test case known/unkown" cases, where the "input string" contains a number of different single
input for a single run of program. In this case we can noticed which single test case cased the problem.

With respect to the overloading of base Checker class, the checker method takes 3 params: (input(s), expected(s), executed(s)), all are string
type. The world is better when all single input are single-line-separated, which usually is unstatisfied. When the single inputs arent, such
as a multiple line description of graph or tree, printing wrong cases' input is impossible. And when ex's single output arent, such as 
a multiple json string of AST, comparing expected and executed is impossbile also.

So It's time to hack!
