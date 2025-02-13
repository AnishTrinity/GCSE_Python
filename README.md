compnum = 50

num = int(input("Enter a number: "))
count = 1
while num != compnum:
  if num < compnum:
    print("Too low, try again")
    count +=1
  else:
    print("Too high, try again")
    count +=1
  num = int(input("Enter a number: "))
print("Well done, you took {} attempts".format(count))
