### for 迴圈(loop)的技巧

```
1.使用for 迴圈(loop)計算1+2+3+.....100
sum=0

for x in range(1,101):
  sum +=x
  
print(sum)

```

```
2.使用for 迴圈(loop)計算1+3+5+7.....+99
sum=0

for x in range(1,101,2):
  sum +=x
  
print(sum)

```

```
3.使用for 迴圈(loop)計算1*3*5*7.....*99
sum=1

for x in range(1,101):
  sum *=x

print(sum)

```

### while 迴圈(loop)的技巧

```
4.使用while 迴圈(loop)計算1+2+3+.....100
sum = 0
x=1

while x < 101:
  sum +=x
  x = x+1
  # x += 1
  
print(sum)

```

```
5.使用while 迴圈(loop)計算1+3+5+7.....+99

sum = 0
x=1

while x < 101:
  sum +=x
  x = x+2
  # x += 1
  
print(sum)
```

```
6.使用while 迴圈(loop計算1*3*5*7.....*99
total = 1
x=1

while x < 101:
  total *=x
  x = x+2     # x += 2
  
print(total)

```
