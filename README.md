Q =float(input("enter number:"))
m = Q
while True:
    s =input("do you like countinue?(no/yes)")
    if s.lower()=="no":
        break
    Q =float(input("enter number:"))
    if Q<m :
        m=Q

print(m,"min:")
