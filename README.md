# Droid-Login-System
I had literally forgotten about the def function, so I decided to build a login system to remind myself.
print ("Droid Login System")
def login():
    while True:
        username = input("Enter Username: ")
        password = input("Enter Password: ")
        if username == "admin" and password == "password123":
         print("Login Successful!")
            
        else:   
         print("Login Failed. Please try again.")
        break
login()
