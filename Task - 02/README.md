## APPRAOCH
**Code -1**

T = int(input())
for i in range(T):
    x = int(input())
    if x<=10:
        print("YES")
    else:
        print("NO")

**Code - 2**

T = int(input())
for i in range(T):
    X,Y = map(int, input().split())
    if Y<=X:
        print(Y)
    elif X<=Y:
        print(X)

**Code -3**

T = int(input())
for i in range(T):
    N,X,Y = map(int, input().split())
    if ((N+1)*Y)/X >= 1:
        print("YES")
    else:
        print("NO")

**Code -4**

T = int(input())
for k in range(T):
    X,Y= map(int,input().split())
    a = ((X-1)/10)+1
    b =  X/10
    if X>=a and X<=b:
        a==b
    c = ((Y-1)/10)+1
    d = Y/10
    if Y>=c and Y<=d:
        c==d
    print(abs(int(c)-int(a)))

**Code-5**
**Code-6**



