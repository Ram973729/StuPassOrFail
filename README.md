# StuPassOrFail
sno=int(input('Enter sno:'))
sname=input('Enter Student Name:')
group=input('Enter Group:')
s1=int(input('Enter English marks:'))
s2=int(input('Enter Maths marks:'))
s3=int(input('Enter Computer marks:'))
print(sno)
print(sname)
print(group)
if s1>=35 and s2>=35 and s3>=35:
    print('Pass')
else:
    print('Fail')
