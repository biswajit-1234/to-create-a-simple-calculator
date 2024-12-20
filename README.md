#Calculator project
def calculator():
    a=int(input("Enter the  1st value:"))
    b=int(input("Enter the 2nd value:"))
    print("Enter 1. For Addition \n 2. For Substraction\n 3. For Division\n 4. For float division\n 5. For power\n 6.For  Reminder \n 7. For Exit")
    c=int(input("Enter your choice:"))
    match c:
        case 1:
            print(f"Addition of {a} and b is {a+b}") 
        case 2:
         print(f"Substaction  of {a} and b is {a-b}") 
        case 3:
         print(f"division of {a} and {b} is{a/b}")
        case 4:
          print(f"Floating division of {a} and {b} is {a//b}")
        case 5:
          print(f"Power of {a} and {b} is{pow(a,b)}")
        case 6:
          print(f"The reminder of {a} with {b} is {a%b}")
        case 7:
         print("")
                  
calculator()


            
