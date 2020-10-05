# Convert-Miles-to-Kilometres-and-vice-versa-

q1 = input("""Hello! Do you want to convert:
A: Kilometres to Miles or
B: Miles to Kilometres 

Please enter A or B:
""")

if q1 == "A":
  q2 = int(input('''Please enter the Kilometres that you want to convert to Miles: '''))
  miles = q2*0.621371
  print('{} kilometres is {} miles'.format(q2, miles))

else:
  q2 = int(input('''Please enter the Miles that you want to convert to Kilometres: '''))
  km = q2*1.60934
  print('{} miles is {} kilometres'.format(q2, km))
