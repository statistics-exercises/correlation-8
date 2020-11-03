# Generating linearly correlated random variables

The key to solving all of the exercises on correlation prior to this one was to generate two independent, uniform random variables.  Furthermore, you should have seen that you can ensure that a random variable `X`, can be generated so that `X>a` and `X<b` by using the following code:

````
 X = a + (b-a)*np.random.uniform(0,1)
 ````

In this exercise, we are going to make things slightly more different as the two random variables we are going to generate will need to be correlated.  If you press run on the run you will see two straight lines will appear.  Your task is to generate 100 uniform random variables that lie between these two lines.  To help you complete this task the equations of the lines are:

````
y = x - 1
y = x + 1
````

Furthermore, as with all the other exercises you should not need to use any conditional (if) statements in your program.  In fact the key is recognising that your two variables need to be correlated.
