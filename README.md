def funtask(num):
    if(num>100):
        return num-5
    return funtask(funtask(num+11));

print(funtask(45)) 
