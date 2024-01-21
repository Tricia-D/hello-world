# hello-world
#My first repository
#I'm happy to be here.
#If the bill was $150.00, split between 5 people, with 12% tip. 
print("Welcome to the tip calculator.")
bill=float(input("What is the total bill? $"))
tip=float(input("What percentage tip would you like to give? 10, 12, or 15 or more? "))
people=int(input("how many people to split the bill? "))
total_bill=(bill*(1+tip/100))/people
#format value to 2 decimal places
total_bill_format="{:.2f}".format(total_bill)
print(f"Each person should pay: ${total_bill_format}")
