# Arthimetic-Progression
first_number=int(input("enter the first number"))
cd=int(input("enter the common differnce:"))
total_terms=int(input("enter the no of terms:"))
current_value=first_number
for i in range(0,total_terms):
    print(current_value ,end=" ")
    current_value=current_value+cd
