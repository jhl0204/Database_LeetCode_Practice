### Compilation of Links to Explanations of Various SQL Concepts




1. [Cartesian Products in SQL - Youtube Video](https://www.youtube.com/watch?v=58i-sZ6h1mI)

**Definition:** *Cartesian Product* of A and B is the set of all possible ordered pairs where the first element comes from the first set (A) and the second element comes from second set (B)

 \* for n --> set of ordered tuples

    - Example of Cartesian Product:   
    A = {apple, pear, orange}  
    B = {cat, dog}

    A x B =   
    {(apple,cat),(apple,dog),  
     (pear,cat),(pear,dog),  
     (orange,cat),(orange,dog)}


Joining Tables is equivalent to forming the Cartesian product of the tables in the **FROM** clause

Then, the remaining clauses are applied in the following order:

- WHERE
- GROUP BY
- HAVING
- SELECT
- ORDER BY

(also refer to my gist on [Order of Execution SQL](https://gist.github.com/jhl0204/6b2025f9cbed54150b6c6a526efe813f))





_____

2.
