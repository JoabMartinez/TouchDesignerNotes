##These are my notes for Touch Designer (Real Time Engine)

###9/19/18 ####https://youtu.be/d5viCICEJUw #####Python in TouchDesigner |Variables|

When you have a table and you are writing a script, you are able to change the values of the table without changing any of the code by

ex. 

    in the code it has to say
    red_marbles = op ('table_marbles') ['red', 1]
    and in the table it says 
    0          1
    red       10
    
    so that means that red is the variable and that wherever the 1 is on top then touchdesigner will look for red and see where 1 is hitting which is 10 in this example 
    
When you have a picture or a video, you can change the parameter via code with

    op('level1').par.opacity = 0

**Terms**

**op** - Operator, it looks for the operators in TouchDesigner like a table or a moviefilein

**par** - Parameter, you are able to change the parameter within the code of anything like a level

**#** - comment out a line
