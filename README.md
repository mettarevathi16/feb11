sno = int (input ('Enter student no: ')) 
sname = input (' Enter student name: ') 
sgroup =input (' Enter student group: ')
s1 = int (input (' English marks: '))
s2 = int (input ('EE marks: ')) 
s3 = int (input ('OB marks:')) 
s4 = int (input ('maths marks: ')) 
s5 = int (input ('chemistry marks:')) 
s6 = int (input ('computers marks: ')) 
total=s1+s2+s3
avg=total/3
if avg>=91:
    print('O-grade')
elif avg>=81:
    print('A-grade')
elif avg>=71:
    print('B-grade')
elif avg>=61:
    print('C-grade')
elif avg>=51:
    print('D-grade')
elif avg>=40:
    print('pass')
else:
    print('fail')
