# Eligibility.
m1=input("Enter marks in Physics: ")
m2=input("Enter marks in Chemistry: ")
m3=input("Enter marks in Mathematics: ")
m4=input("Enter marks in English: ")
m5=input("Enter marks in Extra Subject: ")
t=(float(m1)+float(m2)+float(m3)+float(m4)+float(m5))
p=float(t/5)
print("Total: ",t,end=('\n'))
print("Percentage: ",p,end='%\n')
if p>=90:
    print("CSE")
elif p>=80:
    print("ECE")    
elif p>=70:
    print("ME")
elif p>=60:
    print("CE")
else:
    print("SORRY!")
print("All the best for future.")            
