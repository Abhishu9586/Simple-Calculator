# Simple-Calculator
#simple calculater

print("CALCULATOR")
a=int(input("enter your 1st number:")) #user 1st number
b=int(input("enter your 2nd number:")) #user 2nd number

#created arithmetic choice through BODMAS 

print("1.Div")
print("2.Mul")
print("3.Add")
print("4.Sub")

#user choice 

user_choice=int(input("choose your choice: "))
if user_choice == 1:
  print("Division of",a,"and",b,"is",a/b)
if user_choice == 2:
  print("Multiplication of",a,"and",b,"is",a*b)
if user_choice == 3:
  print("Add of",a,"and",b,"is",a+b)
if user_choice == 4:
  print("Difference of",a,"and",b,"is",a-b)
if user_choice >= 5:
  print("choose valid arithmetic operation option")
if user_choice < 1:
    print("choose valid arithmetic operation option")
