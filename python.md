author: Hans Aparicio
summary: Introduction to Data Science and Big Data with Python
id: data-science-by-python-hansaparicio
categories: codelab,markdown
environments: Web
status: Published

# Introduction to Data Science and Big Data with Python

## Data Science and Big Data
Duration: 0:1:00

### What is Data Science?
Data Science is to extract useful knowledge from our data 

### Some examples of systems that use or was made with Data Science
* *Recomendations systems*: Spotify, Facebook, Netflix, Amazon, Mercado Libre, Google 
* *Speech recognition systems*: Siri, Cortana, Google Now, Amazon Echo, ALexa
* *Email clasification*: Gmail, Hotmail, Yahoo! 
* *Weather prediction*: Waze, Uber, Cabify, Google Maps 
* *Fraud detection*: PayPal, Mercado Libre, bancos 
* *Online advertising*: Google Ads, Facebook 
* *Chatbots* 
* *Early disease detection* 
* *Large-scale opinion analysis* 

### What do the Data Specialist do?
* *Data Scientist*: Collect, clean and sort the data to use in various algorithms. 
* *Data Engineer*: Person that have the responsability to make the infrastructure to obtain and view the data.
* *Data Architect*: The person how makes and mantains the infrastructure to save the data

### What is the programming?
Its a discipline ... to solve problems?

* Input
* Output
* Math operations
* Conditional execution
* Bucles

## Values, Variable, Operators and Expresions
Duration: 0:01:00

### Values
```
print("Hello world")
print(type("Hello world"))
```
### Variable
Is a container where we can save data, the gold rule the sign `=` in programing languages is assignment action.
```
any_var = input("please write any number value: ")
any_var = 5 + any_var
print(any_var)
```
We can assign many types of data inside a variable; the primitive types are:
* int
* string
* boolean
* float
* list
### Operators and Expresions
1. Aritmetic: 
```
print(2 + 5)
print(5 - 3)
print(3 * 3)
print(10 / 4)
print(10 // 4)
print(10 % 4)
print(2**8) 
```
2. Logic:
```
true AND true = true
true OR false = true
NOT true = false
```
3. Comparatives:
```
print(5 == 6)
print(5 != 6)
print(5 < 6)
print(5 > 6)
print(5 <= 6)
print(5 >= 6)
```


## Control structures and Loops
Duration: 0:01:00

### If and Else statement
```
if `<condition>`:
    ...
else
    ...
```
### List
A list is a group of data inside a sorted collection, the declaration form uses `[]` sign to set data separated by `,` look the follow example: 
```
students = ["Diomar", "Maria", "Giovanna", "Amy"]
```
We can access a specific data through use the index e.g:
```
print(students[0])

Diomar
```
We can access to a range or sub collection of this data through use `:` sign e.g:
```
print(students[0:2])

["Diomar", "Maria", "Giovanna"]
```
### For loop
```
for student in students:
    print("Hola mundo" )

Diomar
Maria
Giovanna
Amy
```