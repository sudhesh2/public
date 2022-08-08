# public 
a=10
b=11
sum=a+b
print("sum of the number:",sum)

number=[11,88,9,25]
print("original list items are:",number)
number.append(220)
print("append number:",number)
number.append(44)
print("append number:",number)
number.append(389)
print("append number:",number)


number=[11,88,9,25]
print("original list items are:",number)
a=[223,9877]
number.extend(a)
print("extend number:",number)
b=[35654,4758]
number.extend(b)
print("extend number:",number)

num=1234
reversed_num=0
while num !=0:
    digit =num%10
    reversed_num=reversed_num*10+digit
    num//=10
print("reversed number:"+str(reversed_num))

