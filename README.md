# sarakanam-manoj-kumar_700741915_assignment2
program1

rows = 5
for i in range(0, rows):
    for j in range(0, i + 1):
        print("*", end=' ')
    print("\r")

for i in range(rows, 0, -1):
    for j in range(0, i - 1):
        print("*", end=' ')
    print("\r")
    
    program2
    
    my_list=[10,20,30,40,50,60,70,80,90,100]
for i in range(1,len(my_list),2):
    print(my_list[i])
    
    program3
    
    x = [23, 'Python', 23.98]

types = []
for item in x:
    types.append(type(item))

print(x)
print(types)

program4

def get_unique_list(input_list):
    return list(set(input_list))

sample_list = [1, 2, 3, 3, 3, 3, 4, 5]
unique_list = get_unique_list(sample_list)

print(unique_list)

program5

def string_test(s):
    d={"UPPER_CASE":0, "LOWER_CASE":0}
    for c in s:
        if c.isupper():
           d["UPPER_CASE"]+=1
        elif c.islower():
           d["LOWER_CASE"]+=1
        else:
           pass
    print ("No. of Upper case characters : ", d["UPPER_CASE"])
    print ("No. of Lower case Characters : ", d["LOWER_CASE"])

string_test('The quick Brown Fox')
