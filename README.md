# euler7

list = [2]
x = 3
#z = 1
variable = True
while variable == True:
    y = x - 1
    while x % y != 0:
        #x / y
        y = y - 1
        if y == 1:
            list.append(x)
            print x
            #print "list", list
            break
    x = x + 1
    for counter, value in enumerate(list):

        if counter == 10000:
            print counter, value
            variable = False
        else:
            continue
