# paycalc
#Calculates 40 hours of pay 

hours = float(input("How many hours were worked? "))
rate = float(input("At what rate of pay? "))

standardpay = (hours)*(rate)

overtimepay = (40 * rate) + ((hours - 40) * (rate * 1.5))

if hours >= 40: 
	print (overtimepay)
else:
	print (standardpay)
