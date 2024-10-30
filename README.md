# Python Data Structures: Code Snippets

This repository contains essential code snippets for working with Python data structures, including Lists, Tuples, Dictionaries, and Sets.

---

### Code Snippets

---

**Lists**

1. Create a List  
   `my_list = [1, 2, 3, 4, 5]`

2. Append to List  
   `my_list.append(6)`

3. Extend List  
   `my_list.extend([7, 8, 9])`

4. Insert into List  
   `my_list.insert(1, 99)`

5. Remove from List  
   `my_list.remove(3)`

6. Pop from List  
   `last_item = my_list.pop()`

7. Sort a List  
   `my_list.sort()`

8. Reverse a List  
   `my_list.reverse()`

9. List Comprehension  
   `squares = [x**2 for x in range(10)]`

10. Filter List with Comprehension  
    `even_numbers = [x for x in my_list if x % 2 == 0]`

---

**Tuples**

11. Create a Tuple  
    `my_tuple = (1, 2, 3)`

12. Access Tuple Element  
    `first_element = my_tuple[0]`

13. Unpack a Tuple  
    `a, b, c = my_tuple`

14. Concatenate Tuples  
    `new_tuple = my_tuple + (4, 5)`

15. Nested Tuples  
    `nested_tuple = ((1, 2), (3, 4))`

16. Tuple Comprehension with Generator  
    `gen_tuple = tuple(x**2 for x in range(5))`

17. Check if Element in Tuple  
    `exists = 2 in my_tuple`

18. Find Index in Tuple  
    `index = my_tuple.index(2)`

19. Count Element in Tuple  
    `count = my_tuple.count(2)`

20. Convert List to Tuple  
    `list_to_tuple = tuple(my_list)`

---

**Dictionaries**

21. Create a Dictionary  
    `my_dict = {'name': 'Alice', 'age': 25}`

22. Access Dictionary Value  
    `age = my_dict['age']`

23. Add/Update Dictionary Value  
    `my_dict['city'] = 'New York'`

24. Delete Dictionary Key  
    `del my_dict['age']`

25. Dictionary Comprehension  
    `squared = {x: x**2 for x in range(5)}`

26. Iterate over Dictionary Keys  
    `for key in my_dict.keys(): print(key)`

27. Iterate over Dictionary Values  
    `for value in my_dict.values(): print(value)`

28. Iterate over Dictionary Items  
    `for key, value in my_dict.items(): print(key, value)`

29. Check if Key Exists in Dictionary  
    `if 'name' in my_dict: print("Key exists")`

30. Get Value with Default  
    `city = my_dict.get('city', 'Unknown')`

---

**Sets**

31. Create a Set  
    `my_set = {1, 2, 3}`

32. Add to Set  
    `my_set.add(4)`

33. Remove from Set  
    `my_set.remove(3)`

34. Set Union  
    `other_set = {3, 4, 5}`  
    `union_set = my_set | other_set`

35. Set Intersection  
    `intersect_set = my_set & other_set`

36. Set Difference  
    `difference_set = my_set - other_set`

37. Set Symmetric Difference  
    `sym_diff_set = my_set ^ other_set`

38. Check if Subset  
    `is_subset = {1, 2} <= my_set`

39. Check if Superset  
    `is_superset = my_set >= {1, 2}`

40. Convert List to Set  
    `list_to_set = set(my_list)`

---

These code snippets cover the basics of Python's built-in data structures and common operations performed on them. Each snippet is designed to be clear and standalone, suitable for quick reference or educational purposes.
