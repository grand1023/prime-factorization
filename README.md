# prime-factorization

n=int(input())
i=0
for i in range(2,n):
  if n%i==0:
    print(n,"は素数ではありません")
  else:print(n,"は素数です")  
  break
