# prime-factorization

n=int(input("自然数を入力してください:"))
for i in range(2,n+1):
  for j in range(1,n+1):
    if i%j==0:j=j+1
    else:
      j=j+1
      if n%i==0:
        print(i) 
        n//=i
        i=i
  else:i=i+1
