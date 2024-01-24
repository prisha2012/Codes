s,i,c=input(),0,1
while i<len(s):
    j=i+1
    while j<len(s) and s[i]==s[j]:j,c=j+1,c+1
    print(s[i]+(str(c) if c>1 else''),end="")
    i,c=j,1
