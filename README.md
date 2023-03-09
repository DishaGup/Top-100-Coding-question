# Top-100-Coding-question
<p>Use a Pen&Paper to solve it then Calculate Your Scores </p>

1- Finding the HCF of two numbers-
    
    1. METHOD-  Using Loops
<code> 
   num1 = 36
num2 = 60
hcf = 1
for i in range(1, min(num1, num2)):
    if num1 % i == 0 and num2 % i == 0:
        hcf = i
print("Hcf of", num1, "and", num2, "is", hcf)
</code>

     2. METHOD- Using Recursion-
<code> def getHCF(a, b):
    return b == 0 and a or getHCF(b, a % b)
num1 = 36
num2 = 60
print("Hcf of", num1, "and", num2, "is", getHCF(num1, num2))  </code>

2- Finding Lowest Common Multiple (LCM) of two numbers-
   
   1. METHOD- Using Loops
    <code> 
  num1 = 12
num2 = 14
for i in range(max(num1, num2), 1 + (num1 * num2)):
    if i % num1 == i % num2 == 0:
        lcm = i
        break
print("LCM of", num1, "and", num2, "is", lcm)
</code>
   2. METHOD- Using Recursion-
<code> def getHCF(a, b):
    if b == 0:
        return a
    else:
        return getHCF(b, a % b)
num1 = 12
num2 = 14
hcf = getHCF(num1, num2)
# LCM formula
lcm = (num1 * num2) // hcf
print("The hcf is :", lcm)
<span>Correct answers after(number%10)</span>

