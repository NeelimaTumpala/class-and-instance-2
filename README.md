# class-and-instance-2
class Employee:
    pass

emp_1=Employee()
emp_2=Employee()
print(emp_1)
print(emp_2)

emp_1.first = 'neelima'
emp_1.last = 'tumpala'
emp_1.email = 'neelima.tumpala@company.com'
emp_1.pay = '50000'

emp_2.first = 'jyothi'
emp_2.last = 'kapuganti'
emp_2.email = 'jyothi.kapuganti@company.com'
emp_2.pay = '60000'

print(emp_1.email)
print(emp_2.email)


output:
<__main__.Employee object at 0x012E8F58>
<__main__.Employee object at 0x01302718>
neelima.tumpala@company.com
jyothi.kapuganti@company.com
