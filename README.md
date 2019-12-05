## Final Project
 
This project is an analysis of mental health illnesses regarding the states in the United States.

I decided to narrow the data with the states in the United States so there could be a comparison between the same country, the other column chosen was treatment, this was to identify how many of the interviewed workers are actually under treatment.

The biggest issue was to change the data frame into states and the two columns of "YES": Received treatment and  "NO": Not Received treatment, this was done by using a slicing in each case and then joining the two variables. Another point I struggle was that after the slicing was done, the data frame was not conformed correctly until reset.index() was added.

Something interesting to see is that on both graphs appear the same states at first: "CA" and "WA", this means that there are more interviews in those states. 
