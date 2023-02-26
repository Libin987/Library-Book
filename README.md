# Library-Book
#The library book was submitted on due other wise  the fine was charged  
n = int(input("Enter no. of Days :"))

if n >= 5:
    print("You are late.")
    a = range(5, n)
    b = len(a)
    c = b * 0.50
    print(f"The fine for {b} days = Rs:{c}")
else:
    print("You have submitted the book on time.")
