TODO: Reflect on what you learned this week and what is still unclear.

elif - when there's more than one conditions
(  ).append makes an array 

//
number_block = []
    for i in range(10) :
        number_list = []
        for j in range(10) :
            number_list.append(i)
        number_block.append(number_list)
    return number_block

- i remains as the same number, while j will go up by one every time -- hence, append i for number_list so its a constant number

//
for i in range(10) :
        coordinates_row = []
        for j in range(5) :
            coordinates_row.append('(i' + str(i) + ', j' + str(j) + ')')

- coordinates_row.append can be written as 
    ("(i{}, j{})".format(i, j))

//
wedge = []
    for i in range(10) :
        row = []
        for j in range(i + 1) :
            row.append(j)
        wedge.append(row)
    return wedge

- for i in range(10)
    for j in range(i)
    - when u put j in range i, j is limited to the value of i 
        e.g. when i runs for the first time, 
                i = 0
                ∴ j = 0
              when i runs again
                i = 1 
                ∴ j = 1
              and so on ...
            ∴ ['0'], ['0', '1'] ....
