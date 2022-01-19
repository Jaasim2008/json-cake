Simple Python Package That Allows You To Use JSON Freely and Easily

----------------------------

How To Install:

Type `pip install json.cake` Do Download The Package

-------------------------

How to Use:

**the File Should Be In Source Directory First**

First Do `from json_cake import *`
Then `pack = Json_Manager(yourfile.json)`

------------------------

Available Functions To Use:

1. `write_data()`
2. `append_data()`
3. `clear_data()`
4. `get_data()`

`write_data()` requires 2 variables; `key` & `value`.  
Example : `write_data('name', 'John')`   
Output : `{
    "name": "John"
}`

-----------------

`append_data()` requires 2 variables `key` & `value`.   
Example : `write_data('age', 25)`  
Output : `{
  "name": "John",
  "age": [
    25
  ]
}`

------------------------

`clear_data()` Clears all Data in The JSON File

--------------------

`get_data()` requires 1 Variable   
Example : `my_name = pack.get_data('age'), 
print(my_name)`  
Output : `25`

--------------------------------------