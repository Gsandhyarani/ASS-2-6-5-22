# ASS-2-6-5-22
PREAPARE DICTIONARY FOR EMPLOYEE WITH THE FIELDS
e={1:[1,'surya','3-1-2022','Manager',35000,'vizag'],
2:[2,'manoj','3-1-2022','Manager',20000,'mumbai'],
3:[3,'suresh','10-2-2022','Asst Manager',18500,'Kolkata'],
4:[4,'priya','22-2-2022','Store Manager',15500,'Delhi'],
5:[5,'chandhan','13-3-2022','General Manager',18000,'agra']}
x=int(input('Enter a number:'))
print('Enter EMPNO:',e[x][0])
print('Enter EMPNAME:',e[x][1])
print('Date of joining:',e[x][2])
print('EMPDESIGN:',e[x][3])
print('EMPSAL:',e[x][4])
print('City:',e[x][5])
OUTPUT:
Enter a number:4
Enter EMPNO: 4
Enter EMPNAME: priya
Date of joining: 22-2-2022
EMPDESIGN: Store Manager
EMPSAL: 15500
City: Delhi
