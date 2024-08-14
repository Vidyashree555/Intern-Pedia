import random

uppercase_letter="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
lowercase_letter=uppercase_letter.lower()
digits="0123456789"
symbols="!@#$%^&*()+-[]{}:><;"
upper,lower,nums,syms=True,True,True,True
all=""
if upper:
    all+=uppercase_letter
if lower:
    all+=lowercase_letter
if nums:
    all+=digits
if syms:
    all+=symbols
                
length=10
amount=20


                
for x in range(amount):
    password="".join(random.sample(all,length))
    print(password)
    


                    
                    
                
                
            
        
