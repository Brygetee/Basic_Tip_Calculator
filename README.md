# Basic_Tip_Calculator
#Beginner python code for a tip calculator.

#If the bill was $150.00, split between 5 people, with 12% tip. 
#Each person should pay (150.00 / 5) * 1.12 = 33.6
#Format the result to 2 decimal places = 33.60


bill = float(input("How much is your bill?\n$"))
people = int(input("How many people will be splitting the bill?\n"))
tip = int(input("What percentage of your bill will you be tipping? %")) / 100 + 1                                                                                                          
total_bill = (bill/people) * tip
print(f"Each person should pay ${total_bill:.2f}.")

