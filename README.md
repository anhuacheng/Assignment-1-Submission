Assignment 1

Part 1: Documentation for the selected five packaged food items

Given the daily nutritional requirements, I looked for food that at least provides nutritional values for protein, vitamin D, calcium, iron and potassium.  It was difficult to identify food that provides good amount of vitamin D, but in the end, I found the Alaskan Sockeye Salmon at Trader Joe’s which provides 80% of daily required vitamin D per serving.  
Once I identified the food items, I first converted the daily required nutritional values into weekly values per the assignment direction.  The presentation of the nutritional values per serving varies, however.  Some food items provide a fixed value per nutrition, for example 26mg calcium per serving, and others provide a % of daily required nutrition amount, for example 80% of daily value for vitamin D per serving.  For the items where the presentation is based on % of daily value, I used the data provided in the assignment to convert the % into a fixed value.  Lastly, based on how many servings each food item has, I divided the total price by the number of servings to derive at the price per serving.  Please see table 1 for related calculations and table 2 for pictures of all the nutrition facts for selected food items.

Part 2. Document linear programming problem in standard form

The problem we are solving for is what is the minimum weekly food cost in order to meet the required weekly nutritional values.  
The decision variables here are how much I would consume for each of the five food items I selected.  
The objective is to minimize the overall cost.  The cost coefficients here will be the price per serving for each of the five food items.  For example, it will be $2.69 for brown rice.  
The constraints here will be weekly required nutritional value.  Take sodium for an example; for sodium, the weekly consumption cannot exceed 35,000mg.  This is a maximum constraint; therefore, I would take the sodium amount per food item per serving and multiply by the decision variables.  This equation has to be equal to or less than 35,000mg.  For the other nutritional values, they have a minimum constraint.  Take protein for an example; for protein, the weekly consumption has to exceed 350,000mg.  Therefore, I would take the amount of protein per food item per serving and multiply by the decision variables.  This equation has to be equal to or more than 350,000.  Please see table 3 for formula for objective and constraints.

Part 3. Implement the linear programming problem

Once I identified the decision variables, objectives, and constraints, I came up with the relevant python codes to solve for this linear programming problem.  Please see the relevant codes and outputs in GitHub repository.

Part 4. Describe the solution

The solution is indicating that I need 8.75 servings of Alaskan Sockeye Salmon and 119.7 servings of raw almonds per week, and I don’t need to consume any of brown rice, vegetables and fruit in order to meet the weekly nutritional requirements.  The minimum weekly cost is $85.39 based on this diet, which means I would spend $30.24 on Alaskan Sockeye Salmon and $55.15 on raw almonds per week and nothing else on the other three food items.  
It was very surprising to see the solution, and I don’t think I would be able to stick to this dietary plan by only consuming salmon and almonds throughout a week.  By looking at the input data though, I understand almonds provide the most balanced nutritional values at the lowest cost.  The only reason why Salmon would show up in the solution is that that is the only food item that provides vitamin D.  While this dietary plan can minimize the weekly food cost while meeting the nutritional requirements, it lacks variety.  I would say that to be realistic, we would need to add more constraints in order to increase the variety of food choices.

Part 5. Added constraints
To add the constraints, when I set up the variables, I added 1 as the minimum value, which means that I would consume every food item at least once per week.  
With the updated constraints, the weekly food cost is now $87.95.  The solution shows that I would consume 1 serving of brown rice, vegetables and fruit while consuming 116.9 servings of raw almonds and 8.75 servings of salmon.  The solution makes sense in that it’s still trying to minimize the amount of serving I would consume through brown rice, vegetables and fruit and maximize the amount of serving to consume through raw almonds, given raw almonds provide the most needed nutritional values at the lowest cost.  I then updated the minimum values to indicate that I would like to consume brown rice and vegetables twice a day and fruit once a day.  With the updated constraints, it shows that the minimum weekly food cost is $120.63.  This is more reasonable and tolerable for me.  The biggest realization for me through this assignment is that almond is a great food choice in that it’s the cheapest among the food that I like to eat and offers a balanced nutritional value. 



Table 1
![image](https://github.com/anhuacheng/Assignment-1-Submission/assets/156543160/28b61505-764b-4c5a-90be-784376979e88)

 
Table 2





Table 3
 
Table 4
 

