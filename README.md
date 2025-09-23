# Mini_Projects
# Weight converter 
weight = int(input("weight: "))
unit = input("Enter the weight 'lbs' for 'pound' and 'kg' for 'kilograms': ")
if unit.upper() == "lbs":
    converted = weight * 0.45  # converts to pounds
    print(f" The converted weight is {converted} kg")
else:
    converted = weight / 0.45  # converts to kg
    print(f" The converted weight is {converted} lbs")
