# python1
x = int(input("how many candies you want:"))

limit = 9 
i =1
while i <= x:
  if i> limit:
    break
  
  print("candy")
  i = i+1
  
print("This is all we have")

x = int(input("how many candies you want:"))

limit = 9 
i =1
while i <= x:
  if i> limit:
    print("out of stock")
    break
  
  print("candy")
  i = i+1
  
print("This is all we have")
