## STEP 1
Create a variable named base_price to store the base price of the movie ticket and set its value to 15. Create another variable named age to store the user's age and set its value to 21.
## STEP 13
Now, add an else clause to your if statement and print No extra charges will be applied inside the else body. This will print the message only when the extra charges condition is false.

Then, below the else clause, use the print() call to display a message that shows Extra charges: followed by the updated value of extra_charges and check the output in the terminal.
## STEP 14
Extra charges should also apply if the show is in the evening. Update the condition of the if is_weekend: line by using the or operator to combine the existing condition with a second condition checking if show_time is equal to the string Evening.
## STEP 15
Now you will check if the user satisfies the conditions to book a movie ticket. Users with age 21 or above can always book tickets without any restrictions.

Create an if statement to check if age is greater than or equal to 21. Inside the body of the if statement, print Ticket booking condition satisfied to the terminal.

Then, add an else clause to your if statement and print Ticket booking failed due to restrictions inside the else body.
## STEP 16
Users between 18 and 21 can book tickets, but only when the show_time is not Evening.

Update the condition of the if age >= 21: line. Use the and operator to build an expression checking if age is greater than or equal to 18 and show_time is not Evening. Then use the or operator to combine that expression with the existing condition. Do not create new variables.
## STEP 17
There is one more exception to the booking rules. Users between 18 and 21 can book evening shows if they are members.
## STEP 18
Now you will calculate service charges based on the type of seat the user has selected.

Inside the body of the last if statement, below the print('Ticket booking condition satisfied') line, create a variable named service_charges and set it to 0. Make sure to indent your code by four spaces to keep it inside the outer if statement body.

Then, create a nested if statement to check if seat_type is equal to Premium. Inside the body of the nested if statement, update the service_charges value to 5.
## STEP 19
Still inside the body of the outer if statement, add an else clause to the nested if seat_type == 'Premium': statement and update the service_charges value to 1 inside the else body. Make sure to keep the else indented by four spaces to stay inside the outer if statement body.
## STEP 20
Still inside the body of the outer if statement, add an elif clause between the if seat_type == 'Premium': and else: lines and check if seat_type is equal to Gold. Inside the body of the elif clause, update the value of service_charges to 3.

Below the nested if...elif...else statement, use the print() call to display a message that shows Service charges: followed by the updated value of service_charges. Then, check the output in the terminal.
## STEP 21
In this final step, you will calculate the final price of the movie ticket using the values calculated in the previous steps.

The final ticket price is calculated by adding the extra charges and service charges to the base price, and then subtracting the discount.

Inside the body of the last if statement, below the print('Service charges:', service_charges) line, calculate the final price of the ticket and store it in a variable named final_price.

Finally, print a message that shows Final price of ticket: followed by the value of final_price.