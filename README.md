(a)str="";    
for Row in range(0,7):    
    for Col in range(0,7):     
        if ((Col == 1 or Col == 5) or (Row == 3 and Col > 1 and Col < 6)):  
            str=str+"*"    
        else:      
            str=str+" "    
    str=str+"\n"    
print(str);
(b)name = "Hardik"
for letter in name:
    print(letter, end=' ')
(c)def is_palindrome(username):
    username = username.lower()
    return username == username[::-1]
username = input("Enter a Name ")
if is_palindrome(username):
    print(f"{username} is a palindrome!")
else:
    print(f"{username} is not a palindrome.")
