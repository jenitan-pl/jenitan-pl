
--->type conversions<----

a = "hello"
print(a,type(a))
print(bool(a))

b = 354
print(b)
print(float(b))

c = int(190)
print(float(c))

d = float(450)
print(d,int(d))

#output 
hello <class 'str'>
True
354
354.0
190.0
450.0 450




stdname =  input("Enter student name:")
stdid =  int(input("Enter student id:"))
stdcourse = input("Enter student course:")
stdavg = float (input("Enter student average:"))
print(stdname)
print(stdid)
print(stdcourse,type(stdcourse))
print(stdavg)

#output 
Enter student name:jeni
Enter student id:07
Enter student course:bca
Enter student average:98
jeni
7
bca <class 'str'>
98.0


stdname = "jeni"
stdid = "0707"
stdcourse = "bca"
print(stdname,type(stdname))
print(stdid,type(stdid))
print(stdcourse,type(stdcourse))

#output
jeni <class 'str'>
0707 <class 'str'>
bca <class 'str'>



