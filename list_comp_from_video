from pprint import pprint

# colors file created from https://simple.wikipedia.org/wiki/List_of_colors

my_list = []

with open("colors.txt", 'r') as file:
    my_list = file.readlines()
    #pprint(my_list)

"""
The first section shows how do a basic list comprehension
"""
"""
for line in my_list:
    print(line)


print("\n\n\nAbove is from standard for loop. Below is from basic list comprehension.\n\n\n")


[print(line) for line in my_list]
"""

"""
The next section shows how to add in conditionals
"""

"""
print("\n\n\nMoving on to standard for loop with conditional.\n\n\n")


for line in my_list:
    if "ro" in line:
        print(line)

print("\n\n\nAbove is from standard for loop with conditional. Below is from basic list comprehension with conditional.\n\n\n")

[print(line) for line in my_list if "ro" in line]

"""


"""
print("\n\n\nMoving on to list created by standard for loop with conditional.\n\n\n")

list_from_standard_loop = []


for line in my_list:
    if "ro" in line:
        list_from_standard_loop.append(line)

pprint(list_from_standard_loop)

print("\n\n\nAbove is from pprint(list_from_standard_loop). Below is from pprint(list_from_lst_comp).\n\n\n")


list_from_list_comp_loop = [line for line in my_list if "ro" in line]

pprint(list_from_list_comp_loop)

"""


print("\n\n\nMoving on to list created by nested standard for loop with conditional.\n\n\n")

list_from_standard_nest_loop = []

for line in my_list:
    if "row" in line:
        for letter in line:
            if "B" not in line:
                list_from_standard_nest_loop.append(letter)

pprint(list_from_standard_nest_loop)

print("\n\n\nAbove is from pprint(list_from_standard_nest_loop). Below is from pprint(list_from_list_comp_nest_loop).\n\n\n")


list_from_list_comp_nest_loop = [letter for line in my_list if "row" in line for letter in line if "B" not in line]

pprint(list_from_list_comp_nest_loop)


