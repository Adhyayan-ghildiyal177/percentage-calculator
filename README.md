# percentage-calculator
marks1=int(input("enter your english marks="))
marks2=int(input("enter your maths marks="))
marks3=int(input("enter your physics marks="))
marks4=int(input("enter your chemistry marks="))
marks5=int(input("enter your french marks="))
p=((marks1+marks2+marks3+marks4+marks5)/500)*100
if(p>100):
    print("technical error! try using two digit term")
elif(p>90):
    print(p,"you got A grade")
elif(p>80):
    print(p,"you got B grade")
elif(p>70):
    print(p,"you got C grade")
elif(p>60):
    print(p,"you got D grade")
elif(p>33):
    print(p,"you got E grade")
else:
    print(p,"you are fail")

