print ("hello world")
def multiply_numbers(number1, number2):
	answer = number1 * number2
	print(number1, " x ", number2, " = ", answer)

val1=int(print("enter an integer here:"))
val2=int(print("enter second integer here:"))
ask=str(print("do you want to multiply these two numbers?:"))
for ask in ["y","Y","yes","Yes","YES"]:
  multiply_numbers(val1,val2)
  
else :
exit()
  

