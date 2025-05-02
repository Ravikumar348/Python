# Python
#dictionary operations
person={'name':'Ravi','age':21,'city':'mumbai'}
print(person)
print("accessing and modify the person age...")
person['age']=31
print(person)
print("adding and removing items")
person['email']='dwarapudiravikumar1@gmail.com'
print(person)
del person['city']
print(person)
print("All keys and values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get('age'))
