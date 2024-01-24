n=int(input())
height=[int(input()) for _ in range (n)]

def counts(n,height):
    max_height=max(height)
    count=height.count(max_height)
    return count
result=counts(n,height)
print(result)
