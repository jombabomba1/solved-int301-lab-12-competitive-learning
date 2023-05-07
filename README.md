Download Link: https://assignmentchef.com/product/solved-int301-lab-12-competitive-learning
<br>
<span class="kksr-muted">Rate this product</span>

Competitive Learning

To demonstrate the competitive networks ability to cluster data, a 2-dimensional dataset consisting of 6 Gaussian distributions with small widths will be used. Use the function loadclust1 to get the data and Matlab’s plot function to visualize it, e.g.

<pre>               &gt;&gt; [P,T] = loadclust1(200);               &gt;&gt; plot(P(1,:),P(2,:),'b*');</pre>

Use m-file syn_comp.m in the next 3 exercises.

Exercise 1: Use 100-200 data from the data set, with 6 output neurons and default values for the learning parameters. Does it work?(Note: after setting the parameters, remember to ‘Hit a key to continue’ in the command window; it is also recommended to keep Figure 1 on top to observe the position changes of output neurons.)

Exercise 2: Use 100-200 data from the data set and 6 output neurons, but try different settings of the learning parameters and conscience learning parameter. Especially, turn off the conscience learning parameter (type ‘n’ for ‘Use default learning parameters’ and type 0 for ‘Conscience learning rate’) to see if ‘dead neurons’ appear. (Note: use “help learncon” in command window if you want to know more about conscience learning parameter.)