 a=120
print("your account balance is::",a)
b=int(input());
print("enter amount you want to withdraw::",b);
c=a-b-0.5;
if(b>a):
    print("not enough balance.your balance is",a)
else:
    if(b%5==0):
        print("\nafter your withdraw balance is::",c)
    else:
        print("\nwithdraw not successed.your account balance is",a)
