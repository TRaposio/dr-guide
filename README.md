# dr-guide
A tutorial for solving the Rubik's Cube with as few moves as possible through the Domino Reduction approach.

Quoting the [speedsolving wiki](https://www.speedsolving.com/wiki/index.php/Domino_Reduction)
> **Domino Reduction** or **DR** is a technique invented by Morwen Thistlethwaite[^1]. It is employed by computer algorithms, speedsolvers and fewest move solvers to bring the 3x3x3 cube into a state similar to the [Rubik's Domino](https://www.speedsolving.com/wiki/index.php/Rubik%27s_Domino). This is accomplished by orienting all the corners and performing 2-axis EO, reducing the cube from <U,D,L,R,F,B> to <U,D,L2,R2,F2,B2>.

Domino Reduction was first implemented in 1981 to allow computer algorithms to solve the cube efficiently. It was mentioned in the Fewest Moves Challenge [^2] context for the first time in 2007, but was considered a worse approach than general blockbuilding techniques until 2019. This guide aimed at changing this preconception. 

As of today, all the world class solvers use Domino Reduction as their main method.

To have a better understanding of the method and the concepts presented in the guide, you should be familiar with Sebastiano Tronto's [FMC tutorial](https://fmcsolves.cubing.net/).

[^1]: [Thistlethwaite's Algorithm](https://www.speedsolving.com/wiki/index.php/Thistlethwaite%27s_algorithm)
[^2]: [Fewest Moves Challenge](https://www.speedsolving.com/wiki/index.php/Fewest_Moves_Challenge)


