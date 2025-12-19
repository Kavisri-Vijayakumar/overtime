# overtime
ovpay=0
sum=0
for i in range(1,11):
    print("Enter Working Hours of Emp ",i,":")
    h=int(input())
    
    if(h>40):
        extra=h-40
        ovpay=extra*12
        print("Over time pay of emp ",i," is ",ovpay)
        sum=sum+ovpay
    else:
        print("No Overtime Pay")
print("Total Overtime Pay of all employees : ", sum)

Output
Enter Working Hours of Emp  1 :
10
No Overtime Pay
Enter Working Hours of Emp  2 :
45
Over time pay of emp  2  is  60
Enter Working Hours of Emp  3 :
46
Over time pay of emp  3  is  72
Enter Working Hours of Emp  4 :
47
Over time pay of emp  4  is  84
Enter Working Hours of Emp  5 :
41
Over time pay of emp  5  is  12
Enter Working Hours of Emp  6 :
11
No Overtime Pay
Enter Working Hours of Emp  7 :
87
Over time pay of emp  7  is  564
Enter Working Hours of Emp  8 :
85
Over time pay of emp  8  is  540
Enter Working Hours of Emp  9 :
96
Over time pay of emp  9  is  672
Enter Working Hours of Emp  10 :
69
Over time pay of emp  10  is  348
Total Overtime Pay of all employees :  2352


