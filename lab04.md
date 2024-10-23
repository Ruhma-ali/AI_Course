# # code1

num1=int(input("Enter Number1:"))
num2=int(input("Enter Number2:"))

if(num1>num2):
    print(num1,"is greater than",num2)
elif(num1<num2):
    print(num1,"is smaller than",num2)
else:
    print("Numbers are equal")
    
    
# code2

score = float(input("Enter your score (0-100): "))
if score >= 90:
    print("You got an A.")
elif score >= 80:
    print("You got a B.")
elif score >= 70:
    print("You got a C.")
elif score >= 60:
    print("You got a D.")
else:
    print("You got an F.")


# code3
weather = input("Enter the weather (sunny, rainy, snowy): ").lower()

if weather == "sunny":
    print("It's a beautiful day! Go outside and enjoy!")
elif weather == "rainy":
    print("Don't forget your umbrella!")
elif weather == "snowy":
    print("Time for a snowball fight!")
else:
    print("I don't have advice for that kind of weather.")



# logical conditions 
print(3==2 and 3==4)
print(3==3 or 3==4)
print(not 3==4)

# 80 
