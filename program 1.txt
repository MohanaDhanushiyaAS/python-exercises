Python 3.12.1 (tags/v3.12.1:2305ca5, Dec  7 2023, 22:03:25) [MSC v.1937 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information.
>>> d=int(input("Enter Number of days:"))
Enter Number of days:10
>>> if(d<=5):
...     fine=d*0.50
...     print("Enter:"float(fine))
...     
SyntaxError: invalid syntax. Perhaps you forgot a comma?
>>> if(d=5):
...     
SyntaxError: invalid syntax. Maybe you meant '==' or ':=' instead of '='?
>>> if(d<=5):
...     fine=d*0.50
...     print("Fine:,",float(fine))
... elif(d>5 and d<=10):
...     i=d-5
...     fine=(i*1)+(5*0.5)
...     print("Fine:",float(fine))
... elif(d>10 and d>=30):
...     i=d-10
...     fine=(i*5)+(5*0.50)+(5*1)
...     print("Fine:",float(fine))
... else:
...     i=d-10
...     fine=(i*5)+(5*0.5)+(5*1)
...     print("Your Membership is cancelled")
...     print("Fine amount(Rs):",float(fine))
... 
...     
Fine: 7.5
