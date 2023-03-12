# Codeclause_project_Random-password-generator

#random password generator
import random
lower = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*()."
 #upper = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
 #number = "0123456789"
 #symbol = "!@#$%^&*()."
 #string = lower + upper + number + symbol
string = lower
length = 16
password = "".join(random.sample(string,length))
print("Your new password is :"+password)
