# First-Project
First project to test Github

def fibonacci(x):
    if x==1:
        print "1"
    elif x==2:
        print "1 1"
    else:
        list = [1,1]
        final = ""
        for i in range(2,x):
            list.append(list[i-1]+list[i-2])
        for j in range(len(list)):
            final+=str(list[j])+" "
        print final
