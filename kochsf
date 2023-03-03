s=turtle.getscreen()
t=turtle.Turtle()
#import math

#phrase formation
k=float(input("enter limit:"))
i=0
#m=math.pow(4,k)
output=["f","f","b","b"]
phrase=output
while(i<=k):
    outputc=[]
    q=len(phrase)
    n=0
    while(n<q):
        if(phrase[n]=="f"):
            outputc=outputc+["b"]
        elif(phrase[n]=="b"):
            outputc=outputc+["f"]
        n=n+1
    phrase=phrase+outputc
    i=i+1
l=0
g=len(phrase)
while(l<=(g-1)):
    if phrase[l]=="f":
        t.forward(6)
        t.left(60)
    elif phrase[l]=="b":
        t.backward(6)
        t.left(60)
    l=l+1
