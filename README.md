## How to find the data type of user input:

###Step 1:  
  ***use input() to take in the input of a user and store it as a variable***
```python
first_name = input("Please enter your first name: ")
```  

###Step 2:
   ***Use type() to detect the type of data provided***
```python
example = type(first_name)
```

###Step 3:  
   ***Print this type back to the user in a readable format***
```python
print(first_name, "is", type(first_name))
```