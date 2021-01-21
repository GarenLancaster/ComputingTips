# 变量交换
`a,b=b,a`
# 字符串链接
print("Hi,I'm {}.i {} old , from {}}".format(name,age,city))
print("Hi,I'm {0}.i'm {0}".format(name,age,city))
print(*f*"Hi ,I'm {name}.I'm {age+1} old.") **3.6以上**
# yield
马上使函数返回一次，要输出0到10不再需要函数f（）返回数组
```
def f(n):
  a=0

  for _ in range(n):
    yield a
    a = a + 1

for i in f(10):
  print(i)
```
# 倒序输出list，并带上所应号
```
for i,x in enumerate(reversed(listf)):
  print(i,x)
```
#排序输出list
```
for x in sorted(listf):
  print(x)
```
#字典合并
```
a = {...}
b = {...}

c = {**a,**b}
```
