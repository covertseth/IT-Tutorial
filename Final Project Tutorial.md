<H2> Object Position Calculator(OPC) Tutorial
<H4> By: Seth Covert

<H4> Purpose
>In this tutorial I'll giving you step by step instruction on how to complete the project OPC.

<H4> Objective
>In this project your given 4 key factors, Initial Position(X0), Initial Velocity(V0), Acceleration(a), and Time(t). When these factors are given the correct variable(provided variables) the program calculates an objects last factor, its final position(Xf). This is an easy 3 stap process.

<H4> Steps
>1. First thing you have to realize is all you need to do is ask the user to type in the correct variables for each factor. So simply ask the user to input the variable to each factor(Hint: use the Float method).
2. Once the the factors have been been given the correct input by the user. Apply the factors to the provided math equation(Xf = X0 + (V0 x t) + (.5 x a x t^2) so that the final position can be calculated.
>3. Print/Display the Final Position results.

<H4> Purpose
>This tutorial is for people who need help realizing how simple the project is. So I've provided a stress relieving crazy simplified tutorial for people similar to me. People who see all the numbers and requirments and detailed description and get overwhelmed over a simple project not aware of just how simple it is.

<H4> Targeted Audience
>This tutorial was created for people who tend to over think project and that are very new to coding/python who over think the simple tasks.

<H4> Answers to Steps
<H5>Attempting on your own will be much more rewarding than not trying at all.
>1.initialposition = float(input("Enter Initial Position "))

>initialvelocity = float(input("Enter Initial Velocity "))

>acceleration = float(input("Enter Ojects Acceleration "))

>time_elapsed = float(input("Enter Time that Elapsed "))

>2.finalposition = initialposition + (initialvelocity * time_elapsed) + (0.5 *acceleration * time_elapsed ** 2)

>3.print("\nObjects Final Position is", finalposition)