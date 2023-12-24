# BMI-Calculator-
Description: Calculate Body Mass Index (BMI).
def calculate_bmi(weight, height):
    return weight / (height ** 2)

weight = float(input("Enter weight in kg: "))
height = float(input("Enter height in meters: "))
bmi = calculate_bmi(weight, height)
print("BMI:", bmi)
