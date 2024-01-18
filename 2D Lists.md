n=int(input())
C=input().split()
result= [C[i::n] for i in range(n)]
print(result)
