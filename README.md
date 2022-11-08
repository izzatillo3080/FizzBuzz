for i in range(1,50):
    if  i % 3==0 and i % 5==0:
        print("fiz baz")
    elif i % 5==0:
        print("baz")
    elif i % 3==0:
        print("fiz")
    else:
        print(i)
