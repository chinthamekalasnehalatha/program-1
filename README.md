pi= 3.14
r = float(input("input the radius of the circle:"))
area = pi * r * r
print("Area of the circle with radius r:%.2f" %area)


# TASK-2
filename = input("Input the Filename: ")
f_extns = filename.split(".")
print ("The extension of the file is : " + repr(f_extns[-1]))
