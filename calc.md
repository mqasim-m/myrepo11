# num1 = int (input("Enter first number"))
num2 = int (input("Enter second number"))
print("Which operation to be proceeded")
print ("1. SUM")
print ("2. Sub")
print ("3. MUL")
print ("4. DIV")
opr = int(input("Enter operation no.(1,2,3,4)"))
if opr ==1:
    print("SUM IS ", num1+num2)
elif opr == 2:
    print("Sub =", num1-num2)
elif opr == 3:
    print("Mul =", num1*num2)
elif opr == 4:
    print("DIV =", num1/num2)
