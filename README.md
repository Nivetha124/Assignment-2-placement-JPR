# Assignment-2-placement-JPR

# 1) Print the area up to 4 decimal place
  length=float(input())
  breath=float(input())
  area=length * breath
  print(round(area, 4))

# 2) Program must accept two product’s price, Find the selling price after 10% discount. Print the selling price up to 2 decimal place
  Input 88 23
  Output 79.20 20.70
  price=int(input())
  discount=int(input())
  s=discount/100
  y=price*s
  sellingprice=price-y
  print(round(sellingprice,2))

  def SellingPrice(CP, PP):
    Pdecimal = PP / 100
    res = Pdecimal * CP
    res1=CP-res
    return res1
* Driver code *
if __name__ == "__main__":
    # Get the CP and Profit %
    C = 88
    P = 10
    print(SellingPrice(C, P))

# 3) There are X chocolates available. It has to be distributed equally to Y children. Print the remaining chocolates.

   def remainingchocolate(x,y):
    return x%y
  if __name__ == "__main__":
    x=int(input("enter the no of student"))
    y=int(input("enter the no of chocolate"))
    print(remainingchocolate(x,y))

# 4) Get a word and an integer N. Print the word N times
    n=int(input("enter the word"))
    for i in range(0,n):
        print("Welcome")

# 5) Get N numbers and print the sum of the given N numbers.
   n=int(input("enter the n numbers"))
   m=list(map(int,input("enter the number").split()))
   sum=0
   for i in m:
       sum+=i
   print(sum)

# 6) Get N numbers and print how many are ODD numbers.
    n=int(input("enter the n numbers"))
    m=list(map(int,input("enter the number").split()))
    count=0
    for i in m:
        if i%2==0:
           count+=1
    print(count)

# 7) Find the sum of the series from 1 to N and Print the sum.
    * def printsum(n):
    sum=0
    m=1
    while m<=n:
        sum+=m
        m+=1
    return sum
    n=5
   print(printsum(n))


   * def findSum(n) :
    return n * (n + 1) / 2  
   Driver code
   n = 5
   print findSum(n)

# 8)  Find the factorial of given number:
    def factorial(n):
    product=1
    for i in range(1,n+1):
        product*=i
    return product
    n=int(input("enter the number"))
    print(factorial(n))

   
