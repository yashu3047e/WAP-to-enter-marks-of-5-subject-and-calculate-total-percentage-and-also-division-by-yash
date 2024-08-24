# WAP-to-enter-marks-of-5-subject-and-calculate-total-percentage-and-also-division-by-yash
# WAP to enter marks of 5 subject and calculate total, percentage and also division

name = input("Enter Your Name : ")
import time,sys

def slowprint(text, delay=0.1):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(delay)
    print()  # For a new line at the end

# Usage example
if __name__ == "__main__":
    slowprint(input("Would you like to Check Your All Subject & your Total Marks ? "), delay=0.05)

english = int(input("Enter Your Eng marks : "))
Hindi = int(input("Enter Your hindi marks : "))
Maths = int(input("Enter Your maths marks : "))
science = int(input("Enter Your sci marks : "))
bio = int(input("Enter Your bio marks : "))


Sum_of_all = (english + Hindi + Maths + science + bio)
print("Your Total Marks is ", Sum_of_all)

a = ("Would you like to know your divison ? ")
if a=='yes':
    print(a)
if Sum_of_all>=60:
    print("First Divison")
elif Sum_of_all>=45:
    print("second divison")
elif Sum_of_all>=33:
    print("Third Divison")
else:
    print("faile
