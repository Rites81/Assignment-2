# Assignment-2
About loops
 
 
 marks1=float(input("Enter marks in English::"))
marks2=float(input("Enter marks in Maths::"))
marks3=float(input("Enter marks in Hindi::"))
total=marks1+marks2+marks3
per=total/3
print("Total" , total)
print("average",  average)
if marks1>33 and marks2>33 and marks>33:
    print("Result  : pass")
    if per>=90 and per<=100:
        print("A Grade")
    elif per>=80 and per<=90:
            print("B grade");
        elif per>=60 and per<=70:
            print("C grade");
            else:
                print("Grade D")
                        print("Grade : D")
else:
    print("Result  : Fail")
    print("Grade   : No Grade")
    
    
    
    cost_price=float(input("Enter a bike Price::"))
if cost_price>100000:
 print(f"price of bike_price is {cost_price*1/15}")
elif cost_price>50000 and cost_price<=100000:
 print(f"price of bike-price is {cost_price*0.9}")
elif cost_price<=50000:
 print(f"price of bike_price is {cost_price*1/5}")
else:
    print("Bike Price is under 50000")
    
    
    
    
    city=input("Enter your favorate city::")
if city.title()=="agra":
 print("In Agra beautiful monument is Taj Mahel.")
elif city.lower()=="delhi":
 print("In Delhi beautiful monuments  is Red Fort.")
elif city.lower()=="jaipur":
 print("In jaipur beautiful monument is Jai Mahel.")
else:
 print("Not set in database.")
 
 
 While loop - It is used for execute a set of statement as a condition as long it is while loop is use for stop the  statement. with while we use break and continue statement for some logical coding.
Example::
i=1
while(i<=6):
    print(i)
    i+=1
    
    
    
    
    
    i=1
while i<=5:
    j=1
    while j<=i:
        print(j,end=" ")
        j=j+1
    print("")
    i=i+1
    
    
    
    
    i = 0
 while i < 6:
  i += 1
  print(i)
  
  
  for i in range(1,11):
  for j in range(1,11):
    print(i*j, end=' ')
    print()
    
    
    
    rows=5
for i in range(1,rows+1):
    for j in range(1,i+1):
        print("*",end=" ")
        print(' ')
        
        
 While loop for reverse 10 to 1
        
        i=10
while i>=1:
    print(i)
    i=i-1
    
    i=1
while(i<=10):
    print(i)
    i+=1
