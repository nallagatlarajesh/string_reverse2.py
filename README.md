# string_reverse2.py
#reverse string
def reversestring(st):
    newstr=" "
    length=len(st)
    for i in range(-1,-length-1,-1):
        newstr+=st[i]
    return newstr
#function ends here 
st=input("enetr the string")
#function calling
#st1=reversestring(st)
#print("the reversed string is: ",st1)
reversestring(st)
print("the original string:",st)
print("the reverse string is:",reversestring(st))

#input and out put
#the original string: hai rajesh
#the reverse string is:  hsejar iah
