# Labb1
print("Do you want to know the summ of two cubes' volume? Choose side a please.")
print("put a or b = 0 to end the program")
print("by the way 12^3 + 1^3 = 10^3 + 9^3 = 1729")
a=1
b=1
while b!=0 and a!=0:
    a=int(input("a = "))
    print("Side b")
    b=int(input("b = "))
    c=a**3+b**3
    print("a^3 + b^3 =",c,)
print("Ok, bye!")

n=int(input("Kubsumma = "))

for a in range(1,n):
    for b in range(1+a,n):
        if a**3 + b**3 == n:
            print(a,b)
            
def bebiss(a):
    utrad=""
    for i,v in enumerate(a.split()):
        for v in a.split()[i]:
            if v in konsonanter:
                utrad += v
            else:
                utrad += v
                utrad * 3
                break
    return " ".join(a.split())
