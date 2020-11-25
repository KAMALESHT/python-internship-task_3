# python-internship-task_3

1)Write a Python script to merge two Python dictionaries.

solution:
    
def Merge(dict1,dict2):

    return(dict2.update(dict1))

dict1 = {'a':1,'b':2,'c':2}

dict2 = {'d':4,'e':5,'f':6}

print(Merge(dict1,dict2))

print(dict2)

2)Write a Python program to remove a key from a dictionary.

solution:

dict1={'a':1,'b':2,'c':3}

new_dict1=dict1.pop('b')

print(dict1)

3)Write a Python program to map two lists into a dictionary.

solution:

key_1=['a','b','c']

value_1=[1,2,3]

temp={}

for key in key_1:

    for value in value_1:

        temp[key]=value

        value_1.remove(value)

        break

print(temp)

4)Write a Python program to find the length of a set.

solution:
    
set_1={1,2,3,4}

print(len(set_1))

5)Write a Python program to remove the intersection of a 2nd set from the 1st set.

solution:
    
a={1,2,3,4}

b={4,3,6,5}

print(a-b)
