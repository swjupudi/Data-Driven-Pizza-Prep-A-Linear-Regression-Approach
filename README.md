# Data-Driven-Pizza-Prep-A-Linear-Regression-Approach

Our friend Roberto owns a cozy little pizzeria in Berlin. Every day at noon, he checks
the number of reserved seats and decides how much pizza dough to prepare for dinner. Too
much dough, and it goes wasted; too little, and he runs out of pizzas. In either case,
he loses money.

It’s not always easy to gauge the number of pizzas from the reservations. Many customers
don’t reserve a table, or they eat something other than pizza. Roberto knows that there
is some kind of link between those numbers, in that more reservations generally mean
more pizzas—but other than that, he’s not sure what the exact relation is.

We can fit a machine learning model to try and predict the number of pizzas. We will use
Supervised Learning to solve this problem.

Here's how the first few lines of the data collected:

```text filename="pizza.txt"
Reservations  Pizzas
13            33
2             16
14            32
23            51
```

This data is stored in the file `pizza.txt`.
