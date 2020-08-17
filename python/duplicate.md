# Code snippet for finding duplicate string taking inputs from user
```
def removeDuplicate(str): 
    s=set(str) 
    s="".join(s) 
    print("Without Order:",s) 
    t="" 
    for i in str: 
        if(i in t): 
            pass
        else: 
            t=t+i 
        print("With Order:",t) 
      
str=input("Enter your string: ") 
removeDuplicate(str) 
```
