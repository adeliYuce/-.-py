# -.-py
密码识别
passwd = input("type ypur password")
# check 1
print("check rulr 1")
length = len(passwd)
if len(passwd) < 6 or len(passwd) > 15:
   print(passwd, "is not of valid length", length)
else:
   print(passwd, "is of valid length", length)
   
# check 2
print("check rulr 2")
str_lower, str_upper, n = 0, 0, 0
for i in passwd:
 if i. islower():
    str_lower += 1
 elif i. isupper():
    str_upper += 1
 elif i.isdigit():
     n += 1
     continue
print("Number of loercase in", passwd, str_lower)
print("Number of uppercase in", passwd, str_upper)
print("Number of digits in", passwd, n)
if str_lower > 0 and str_upper > 0 and n > 0 :
         print(passwd,"contains enough of each type of charater")
else:
         print(passwd,"does not contain enough of each type of charater")
         
# check 3
print("check rulr 3")
if passwd.isalnum():
  print(passwd, "is  all alphanumeric")
else :
  print(passwd, "is not all alphanumeric")
  
#check 4
  print("check rulr 4")
def main():
    print(judgment(passwd))
def judgment(passwd):
    for i in range(len(passwd) - 1):
        if passwd[i] == passwd[i + 1]:
            return print(passwd,"contains adjacent duplicates")
        else:
            return print(passwd, "does not contain adjacent duplicates" )
if __name__ == "__main__":
    main()
#check all rules
print("check for all the rules")
if 5 < len(passwd) and len(passwd) < 15 and str_lower > 0 and str_upper > 0 and n > 0 and passwd.isalnum() and passwd[i] == passwd[i + 1]:
      print(passwd, "is valid")
else:
      print(passwd, "is not valid")
