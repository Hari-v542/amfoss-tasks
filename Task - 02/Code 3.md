**Code -3**

    T = int(input())
    
    for i in range(T):
    
        N,X,Y = map(int, input().split())
        
        if ((N+1)*Y)/X >= 1:
        
          print("YES")
          
        else:
        
          print("NO")
