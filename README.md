# Python Projects: BMI Calculator 🐍
This repo contains python code that calculates your BMI.<br>
Run the code.


Python
```python
Height=float(input("Enter your height in centimeters: "))
Weight=float(input("Enter your Weight in Kg: "))
Height = Height/100
BMI=Weight/(Height*Height)
print("your Body Mass Index is: ",BMI)
if(BMI>0):
	if(BMI<=16):
		print("you are severely underweight")
	elif(BMI<=18.5):
		print("you are underweight")
	elif(BMI<=25):
		print("you are Healthy")
	elif(BMI<=30):
		print("you are overweight")
	else: print("you are severely overweight")
else:("enter valid details")
```

Output
```python

Enter your height in centimeters: 150
Enter your Weight in Kg: 40
your Body Mass Index is:  17.77777777777778
you are underweight
```
