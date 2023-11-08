def binary_search(sequence, start_element, key):
    end_element = len(sequence) - 1
    while start_element <= end_element:
        middle_element = start_element + (end_element - start_element) // 2
        if sequence[middle_element] == key:
            return middle_element
        elif sequence[middle_element] < key:
            start_element = middle_element + 1
        else:
            end_element = middle_element - 1
    return -1


# Можно было еще элегантно создать sequence = [i for i range(1, 31)],
# но для наглядности перечислил все элементы
sequence = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10,
            11, 12, 13, 14, 15, 16, 17, 18, 19, 20,
            21, 22, 23, 24, 25, 26, 27, 28, 29, 30]
# Число которое мы ищем
find_element = 24

result = binary_search(sequence=sequence, start_element=0, key=find_element)
print(result)
