string=input()
index=int(input())
result="".join(word[index] for word in string.split())
print(result)
