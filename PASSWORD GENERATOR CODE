import secrets

import string

print("PASSWORD GENERATOR")

print("——————————————————————")

length=int(input("Enter Password Length: "))

print("1.Include uppercase(A-Z)\n2.Include lowercase(a-z)\n3.Include Numbers\n4.Include Symbols\n")

pwdchar = ""

while True:

    choice = int(input("Enter choice: "))

    if choice in (1,2,3,4):

        if choice ==1:

            pwdchar = pwdchar + string.ascii_uppercase

        elif choice ==2:

            pwdchar = pwdchar + string.ascii_lowercase

        elif choice ==3:

            pwdchar = pwdchar + string.digits

        elif choice ==4:

            pwdchar = pwdchar + string.punctuation

      

        next_choice = input("Want to choose another choice? If Yes,Enter(Y)/(N): ")

        if next_choice in ("N","n"):

            break  

    else :

        print("Invalid Input !!!")

passwd = ""

for i in range(length):

    passwd = passwd + (secrets.choice(pwdchar))

print("PASSWORD = ",passwd)
