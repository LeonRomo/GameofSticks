# GameofSticks
sticks = 21
print("-" * 50)

print("There are 21 sticks in the box")
print("One has to pick a number from 1 to 4")
print("The last one to pick the last stick loses")

while True:
    stick_picked = int(input("pick a number from 1 - 4: "))
    if stick_picked < 0:
        continue
    elif stick_picked == 1:
        sticks = sticks - stick_picked
        print ("The number of sticks remaining is ", sticks)
        continue
    elif stick_picked == 2:
        sticks = sticks - stick_picked
        print ("The number of sticks remaining is ", sticks)
        
    elif stick_picked == 3:
        sticks = sticks - stick_picked
        print ("The number of sticks remaining is ", sticks)

    elif stick_picked == 4:
        sticks = sticks - stick_picked
        print ("The number of sticks remaining is ", sticks)    
        break
