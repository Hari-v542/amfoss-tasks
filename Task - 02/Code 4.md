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

