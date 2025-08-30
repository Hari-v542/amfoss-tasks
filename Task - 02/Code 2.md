**Code - 2**

    T = int(input())
    
    for i in range(T):
    
        X,Y = map(int, input().split())
        
        if Y<=X:
        
          print(Y)
          
        elif X<=Y:
        
          print(X)
