#Password checking
pwd="qwerty"
s=input("Enter password")
count=0
while count<3:
    count=count+1
    if s==pwd:
        print("You have successfully logged in")
        break
    else:
        if count>3:
            print("Try again")
        else:
            print("You have been denied access")

