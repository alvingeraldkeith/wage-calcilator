# wage-calcilator
#simply figures out ones pay according to the hours they have worked for

## wage calculator ##
Hours=int(input('enter hours worked'))
regular_rate=10
rate_for_extra_hours=15
regular_pay=Hours*regular_rate
irregular_pay=Hours*rate_for_extra_hours
if Hours>40:
    print(irregular_pay)
else :
    print(regular_pay)
