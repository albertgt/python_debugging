# python_debugging

First steps to debugging

Print out every variable in order to see how it is changing after you modify it.<br>
for example:<br>
  
>hw1 = 90<br>
>hw2 = -4589<br>
>hw3 = 100<br>
>grade = hw1 + hw2 + hw3<br>
  
the above style doesn't help you know what happened if there is a bug with your calculation<br>
but if you do print() to see it at each step then it is very visible which step<br>

>grade = hw1<br>
>print(grade)<br>
>grade = grade + hw2<br>
>print(grade)<br>
>grade = grade + hw3<br>
>print(grade)<br>
  

# Dataframes

print out the columns to a dataframe so you always know what you are dealing with<br>
>print(df.columns)<br>

print out the number of rows and columns of a dataframe so you know its size<br>
>print(df.shape)<br>

preview the data in a dataframe<br>
>print(df.head())<br>
