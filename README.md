# most_frequent
A = input("Please enter a string \n")
def most_frequent(string):
    d= dict()
    for i in string: 
        if i not in d :
            d[i] = 1
        else :
            d[i] = d[i] + 1
    return d
print (most_frequent(A))
