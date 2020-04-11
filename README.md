# password-generator

import random

chars = "abcdefghijklmnopqrstuvwxyz01234567890ABCDEFGHIJKLMNOPQRSTUVWXYZ!@#$%^&*()?"
password_length = 13
p =  "".join(random.sample(chars, password_length))
print (p)

def main():
    f= open("randompassword.txt","w+")
    f.write(p)
    f.close()   
if __name__== "__main__":
  main()
