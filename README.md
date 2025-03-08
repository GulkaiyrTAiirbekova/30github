# 30github
login = input ('Enter your ID name: ')
password = input ('Enter your password: ')

if login == 'Kyrgyzstan':
  if password == 'M1234567':
  else:
    print ('Wrong password or login:')
elif login == 'Central Asia' or ' password == 'M985621491':
  print ("Try again!)
else:
  print('Error')

  
#even or odd day2 
  num=int(input('Enter your number: '))
  if (num%2 ==0):
    print('Even number!')
  else:
  print ('Odd number!')

#in
num = [10, 'Sam',True, 10.5]
if 'Tom' in num:
  print ('Yes')
else:
print ('No')

#in

classmates = ['Tom','Sam',' Sarah', 'Mike',24]
if 'Tom' in classmates:
  print('Yes')
else:
  print ('No')
  
#cycles
numbers = {'str': ' value'}

for number in numbers:
  print(f'Number: {number}')

numbers = [4,2,1,3]
for number in numbers:
  print(f'Number : {number}')

dict = {'str': 'value'}
for i in dict.items():
  print(f' key: {i}, value: {y}')

#reverse 
n = 'World'
res = ' '
for i in n:
  res = i+res
print(res)

word = 'Python'
print(word[::-1])

numbers = [9,5,7,2,5]
first_el = numbers[0]
for i in range(len(numbers)):
  if i < first_el:
    first_el = i
print(first_el)
#
numbers = [9,3,5,646]
numbers.sort()
print(numbers)

print(sorted(numbers))
# 
numbers = [32,45,23,25]

while numbers != sorted(numbers):
  for i in range (len(numbers)):
    if numbers[i] >numbers[i +1]:
      numbers [i] > numbers [ i+1], numbers [i]
print( numbers)


# working with files
# write
file= open('files/text.txt','w')
file.write('Hello')
file.close

# append
file =  open('files/text.txt','a')
file.write(Hello- to the end')
file.close
#read
file.open('files/text.txt','r')
file.read()
file.close()
# working with files
def working_with_files(path_to_file):
file= open(path_to_file,'w')
file.write(data)
file.close()

file= open(path-to-file,'r')
result = file.read()
file.close

return result

# with ...as 
with open ('files/text.txt', 'w') as file:file.write('You can write here')

#

with open('files/text.txt', 'a') as file:
file.write('You can write here')

with open('files/text.txt','r') as file:
file.read()

# reverse 
class  Solution:
  def reverseVowels(self,s: str)-> str:
    s_cpy = list(s)
    vowels = {'a','e','i','o','u'}
    l = 0
    r = len(s)-1

    while l <= r:
      if s_cpy[l].lower()not in vowels and l+1 <len(s_cpy):
        l+=1
      elif s_cpy[r].lower90 not in vowels ans r+>=0:
        r -=1
      else:
      s_cpy[l],s_cpy[r] =s-cpy[r],s_cpy[l]
      l += 1
      r -= 1
    return ' ' , joint(s_cpy)

# import webbrowser

def open_url(link):
  webbrowser.open(link)
my =  input('Enter adress: ' )
if my == 'Youtube'
  open_url(' https://www.youtube.com ' )
elif my == ' Facebook'
  open_url( 'https://www.facebook.com ')
elif my ==  'Linkedin'
  open_url (' https://ru.linkedin.com ')
else:
  print(' Adress is not found' )

# try
def func(a,b):
  result = a/b
  return f'answer: {result}'
  
while True:
  try:
    my_func = func(
      int(input(' First number: ')),
      int(input(' Second number: ')),
      )
      print(my_func)
      break
    except ValueError:
      print(' Wrong Value')
    except ZeroDivisionError:
      print(' Undefined')
#
w = ' Kyrgyzstan'
my_value = input(' : ')
first_el = 0
second_el = 0
for i in w.lower():
  if i in my_value:
    if i == my_value[0]:
      first_el +=1
    else:
      second_el +=1
print (f'{my_value[0]} -{first_el} pcs')
print(f' {my_value[2] -{second_el} pcs')

# Day 7 If-Else
a = int(input('Enter first number: '))
b = int(input('Enter second number: '))
operation = input(' Choose operation (+,-,*,/):')
result = 0
if operation ==' + ':
    result = a+b
elif operation == '-':
    result = a-b
elif operation == ' * ':
    result = a * b
elif operation == '/':
    result = 'a/b'
else:
    print(' Wrong operation ')
print (result)
#
numbers = [12,34,57,67]
result = ' '
for i in numbers:
    if i %2 ==0:
        print('Even')
    else:
        print('Odd')
print(result)
#
number = float(input('Enter number:'))
if number > 0:
  print(f' {number} is positive')
elif number <0:
  print(f'{number} is negative')
else:
  print(f'{number} is zero')

# compare two prices
price1 = float(input('First:'))
price2 = float(input('Second:'))
if price1 > price2:
  print(f'{price1} is greater than {price2}')
elif price 1 < price2:
  print(f'{price1} is cheeper than {price2}')
else:
  print(f' {price1} is equal to {price2}')

# Pass or Fail
score = int(input('Enter your score:'))
if score >=90:
  print ('Passed!, Wellcome!')
else:
  print('Failed! Try next time!')
# Age Eligibility to use an app 
age = int(input('Your age:'))
if age >= 16:
  print('Next step')
else:
  print('You cannot use this app,yet!')

# Divisibility Check
num = int(input('Enter number:'))
if num % 5 ==0:
  print(f'{num} is divisible by 5')
else:
  print(f'{num} is not divisble by 5')
# Simple Password Checker
correct_password = 'Sam909'
password = input('Enter the password:')
if password == correct_password:
  print('Access Granted!')
else:
  print('Access Denied!')

# Data types
# Numeric : int
a = 10
print(type(a))
# float
b = 12.3
print(type(b))
# complex
c= 2+3j
print(type(c))

# String
text = ' Hello,Github'
print(type(text))
# Accessing characters
text = ' Hello,Github'
print(text[0:2])  # Output: He
# String concatenation
first_word = 'Hello'
second_word = 'Github'
message = first_word + ',' + second_word
print(message)
#
first_name = 'Tom'
last_name = 'Jerry'
user_name = first_name + last_name
print(user_name)
# List
my_list = [2,4, 'Tom', 23.6]
# Access elements
print(my_list[2]) # output: Tom
# append
my_list = [2,4, 'Tom', 23.6]
my_list.append('Sam') 
print(my_list)  # output[2, 4, 'Tom', 23.6, 'Sam']
# remove
my_list = [2,4, 'Tom', 23.6]
my_list.remove('Tom')
print(my_list)   # [2, 4, 23.6]
# min and max
my_numbers = [12,3,56,0,7]
print(max(my_numbers)) # outbut:56
print(min(my_numbers)) # output: 0
# Tuple
tuple = (12,34, ' Tom','Sam')
print(type(tuple))
# Access elements
tuple = (12,34, ' Tom','Sam')
print(tuple[1])
# separate tupples
my_tuple =(1,2,3)
for tuple in my_tuple:
    print(tuple)
# Dictionary (dict)
Student = {'name': 'Tom','age': '13', 'course': 'Python'}
print(type(Student))
print(Student ['course'])
# Add a new key-value pair
Student = {'name': 'Tom','age': '13', 'course': 'Python'}
Student['grade'] = 'A'
print(Student)
#
person = {'name': 'Tom','age':'30','city': 'Bishkek'}
print(len(person)) # output:3
#set
my_set = {1,3,5,7,8}
my_set.add(6)
my_set.remove(5)
print(my_set)
#
my_set = {9,8,7,6,4}
for set in my_set:
        print(set)
# union()
set1 ={1,2,3,4}
set2 ={6,7,8,9}
print('Union using():', set1.union(set2))  #output Union using(): {1, 2, 3, 4, 6, 7, 8, 9}
print('difference using():',set1.difference(set2))
print('difference using &:',set2- set1 )
print('Difference using difference():', set2.difference(set1))
print('Using symmetric_difference():', set1.symmetric_difference(set2))
# Boolean (bool)
bool = 5<2
print(bool,type(bool))
#
number= int(input('Enter number:'))
if number > 50:
  print('Number is greated than 50')
else:
  print('Number is less than 50')
  # Loop: For,While
  # for- # access elements  one by one
  numbers =(1,5)
  for in range(1,5):
    print(i,i+1) 
  # 
  my_list = [23,3,2,6,7]
for i in (23,3,2,6,7):
    print(i)
#
names = ('Tom','Sam','Grey')
for name in names:
    print(name)
#
language= 'Python'
for i in language:
    print(i)
# for ...range 
# generate numbers from 0to 5
my_numbers = (0,5)
for i in range(0,5):
  print(i+1) #+1 to include 5 too
#
names = ('Sam','Tom','Mike','Grey')
for name in names:
  if name == 'Grey':
    break
  else:
    print(name)
#
names = ('Sam','Tom','Mike','Grey')
for name in names:
  if name== 'Tom':
    continue
print(names)
#
colors = ('Red','Green','Yellow','Blue')
toys = ('Ball','Baloon','Fox','Snowman')
for color in colors:
  for toy in toys:
    print(color, toy)
print()
# MAP
n = ['1','2','3','4']
def doublt(val):
  return(val*2)
res = list(map(doublt(n))
print(res)
# map with lamda (shorter one)
n = ['1','2','3','4']
res = list(map(lambda x:x *2,n))
print (res)
#
d= [5,4,3,2,1]
res = list(map(lambda x:x *2,d))
print (res) # output:[10, 8, 6, 4, 2]
#
d = ['5','4','3','2','1']
res = list(map(lambda x:x *2,d))
print (res)  #output: ['55', '44', '33', '22', '11']
# map with 2 iterables
a = [1,2,3,5]
b= [9,8,7,4]
res = map(lambda x,y: x+y,a,b)
print(list(res)) #output: [10, 10, 10, 9]
res =map (lambda y,x: y-x,b,a)
print(list(res)) # output [8, 6, 4, -1]
#
a = [1,2,3,4]
b= [5,6,7,8]
res = map(lambda x,y: x+y,a,b)
res = map(lambda y,x : y-x,b,a)
print(list(res))
# map() Converting to uppercase
names = ['tom','sam','mike']
res = map(str.upper,names) #Explanation: The str.upper method is applied to each element in the list fruits using map().
print(list(res))  output: ['TOM', 'SAM', 'MIKE']
#
languages =('python', 'css','html')
res = map(str.upper,languages)
print(list(res)) # output : ['PYTHON', 'CSS', 'HTML']
#
types = ['str','int','tuple','bool']
res = map(str.upper, types)
print(list(res)) # output: ['STR', 'INT', 'TUPLE', 'BOOL']

# MAP Extracting [] characters from strings

a = ['str','int','tuple','bool']
res = map(lambda a:a [0],a)
print(list(res)) # output:['s', 'i', 't', 'b']

res = map(lambda a:a [2],a)
print(list(res)) # output:['r', 't', 'p', 'o']

res = map(lambda a:a [-1],a)
print(list(res)) # output:['r', 't', 'e', 'l']
# MAP .STRIP-Removing whitespaces from strings
words = ['  you', '   are', ' intellegent']
res = map(str.strip,words)
print(list(res))  # output:['you', 'are', 'intellegent']

res = map(str.split,words)
print(list(res))   # output:[['you'], ['are'], ['intellegent']]

# Understanding Exceptions and Syntax Errors

a = input(str('Enter you name:'))
b = int(input('Enter your Code:'))
res = ' '
try:
    print(res)
except ValueError:
    print('Use only letters')
except ZeroDivisionError:
    print( ' Do not divide to zero')
else:
    print('Continue')
#
a = int(input('Enter first number:'))
b = int(input('Enter Second number:'))
result = (a/b)
def divide_numbers(a, b):
    try:
        result = a / b
        return result
    except ZeroDivisionError:
        return 'Cannot divide by zero!'
    except ValueError:
        return 'Invalid input! Please enter numbers.'
print(result)
# Methods
class Car:
    def __init__(self,brand,color):
        self.brand =brand
        self.color=color
    def show_info(self):
        return f'car:{self.brand},Color:{self.color}'
car1 = Car('Porche','Red')
car2 = Car ('Ferrari', 'Black')
print (car1.show_info())   #output: car:Porche,Color:Red
print(car2.show_info())    # output: car:Ferrari,Color:Black
#
class Book:
    def __init__(self, genre,cover):
        self.genre =genre
        self.cover =cover
    def show_info(self):
        return f'Book:{self.genre},Cover:{self.cover}'
book1 = Book('Science_fiction','Hardcover')
book2 = Book('Fantasy','Softcover')
print(book1.show_info()) # output:Book:Science_fiction,Cover:Hardcover
print(book2.show_info())   #output: Book:Fantasy,Cover:Softcover
#
class laptop:
    def __init__(self,firm,condition):
        self.firm = firm
        self.condition= condition
    def show_info(self):
        return f'laptop:{self.firm},condition:{self.condition}'
laptop1=laptop('Mac','New')
laptop2=laptop('Acer','used')
print(laptop1.show_info())
print(laptop2.show_info())
#
class Bird:
    species: ' Aves'
    def __init__(self,name,size):
        self.name=name
        self.size= size
    def show_info(self):
        return f' Bird:{self.name}, Size:{self.size}'
Bird1 = Bird('Eagle','big')
Bird2 =Bird('Sparrow','small')
print(Bird1.show_info())  # Bird:Eagle, Size:big
print(Bird2.show_info()) # Bird:Sparrow, Size:small
#
class Dog:
    species= 'Mammal '
    def __init__(self,name,age):
        self.name =name
        self.age =age
dog1 =Dog('Money','2')
dog2= Dog('Rex','4')
print(dog1.species)  #Mammal
print(dog2.species) #Mammal
Dog.species = ' Predator'
print(dog1.species) #Predator
print(dog2.species) #Predator
class Person:
    population =0
    def __init__(self,name):
        self.name =name
        Person.population += 2
    @classmethod
    def get_population(cls):
        return f'Population:{cls.population}'
    @staticmethod
    def is_adult(age):
        return age>=18
p1 =Person('Sam')
p2 =Person('Tom')
print(Person.get_population())  #Population:4
print(Person.is_adult(20))  #True
#
class Animal:
    def __init__(self,name):
        self.name = name
    def sound(self):
        return 'sound of animal'
class Dog(Animal):
    def sound(self):
        return 'Gaph-Gaph'
dog =Dog('Money')
print(dog.name)  #Money
print(dog.sound()) # Gaph-Gaph
# List Slicing  list[start:stop:step]
my_list = ["y", "w", "q", "r", "s", "t", "u", "v", "i"]
print (my_list[2:6:2]) #['q', 's']
print (my_list[2:8]) #['q', 'r', 's', 't', 'u', 'v']
print (my_list[0:4:7]) #['y']
print (my_list[::-2]) #['i', 'u', 's', 'q', 'y']
# List Methods
my_list = [1, 2, 3, 3, 4]
my_list.append(5)
print(my_list) #[1, 2, 3, 3, 4, 5]
my_list = [9,8,7,6,5]
my_list.extend([14,15])
print (my_list) #[9, 8, 7, 6, 5, 14, 15]
my_list = [9,8,7,6,5]
my_list.remove(7)
print(my_list) #[9, 8, 6, 5]
pop_list = [1,2,3,4]
pop_list.pop()
print(pop_list) #[1, 2, 3]
my_list =[12,23,45,67,89]
my_list.index (45)
print (my_list) #[1, 2, 3, 3, 4] (need to check again)
my_list =[12,23,45,67,89]
my_list.count(2)
print(my_list) # need to check
my_list = [100,3,45,2,55,67]
my_list.sort()
print(my_list) #[2, 3, 45, 55, 67, 100]
my_list = [100,3,45,2,55,67]
my_list.reverse()
print(my_list)  #[67, 55, 2, 45, 3, 100]
my_list = [100,3,45,2,55,67]
my_list.clear()
print(my_list) #[]
# Palindrome ('Mam','dad','madam')
# Step 1: reversed option
w ='level'
reversed_w = w[::-1]
print(reversed_w) #level
# Step2: Step 2: Compare the Original and Reversed String
w= 'level'
if w == w[::-1]:
    print('palindrome')
else:
    print('Not a palindrome') #palindrome
def is_palindrome(word):
    return word == word[::-1]  
print(is_palindrome("madam"))  # True
print(is_palindrome("hello"))
# Checking a Number (Like 121)
def is_palindrome_number(n):
    return str(n) == str(n)[::-1]  # Convert number to string and check
print(is_palindrome_number(121))  # True
print(is_palindrome_number(123))  # False
# leetcode 1
def merge_strings(word1, word2):
    merged = []
    i, j = 0, 0
    while i < len(word1) and j < len(word2):
        merged.append(word1[i])
        merged.append(word2[j])
        i += 1
        j += 1
    merged.append(word1[i:])
    merged.append(word2[j:])

    return ''.join(merged)
word1 = "abc"
word2 = "pqr"
result = merge_strings(word1, word2)
print(result)  #apbqcr

# weight converter
weight = float(input('Enter your weight:'))
unit = input('Kilograms or Pounds? (K or L):')
if input =='K':
    weight = weight * 2.205
    unit= 'Lbs.'
    print(f'Your weight is: {round(weight,1)}{unit}')
elif unit =='L':
    weight =weight/2.205
    unit = 'Kgs.'
    print(f'Your weight is: {round(weight,1)}{unit}')
else:
    print(f'{unit} was not valid')
  ## Temperature Conversion
unit= input("Is temperature in Celsius or Fahrenheit(C/F):")
temp = float(input("Enter the temperature:"))
if unit == "C":
    temp= round((9*temp)/5+32,1)
    print(f"The temperature is Fahrenheit in:{temp} F")

elif unit =="F":
    temp = round((temp-32)*5/9,1)
    print(f"The temperature is Celsius in:{temp}C")
else:
    print(f'{unit} is an invalid of measurement')# Is temperature in Celsius or Fahrenheit(C/F):C #Enter the temperature:32,The temperature is Fahrenheit in:89.6 
# Logical Operators = Evaluate multiple conditions (or,and,or)
temp=  20
is_raining =True
if temp >35 or temp<0 or is_raining:
    print("The outdoor event is cancelled")
else:
    print("The outdoor even is still scheduled") #The outdoor event is cancelled


temp= 20  # i can change temp here , so output will be different
is_sunny= True

if temp >= 28 and is_sunny:
    print("It is hot outside")
    print("It is sunny")
elif temp<=0and is_sunny:
    print("It is cold outside:")
    print("It is Sunny")
elif 28 > temp>0 and is_sunny:
    print("It is warm outside") #It is warm outside
    print("It is sunny") #It is sunny
#
#Logical Operators = Evaluate multiple conditions (or,and,or)
'''temp=  20
is_raining =True
if temp >35 or temp<0 or is_raining:
    print("The outdoor event is cancelled")
else:
    print("The outdoor even is still scheduled")''' #The outdoor event is cancelled
temp= 0  # i can change temp here , so output will be different
is_sunny= False

if temp >= 28 and is_sunny:
    print("It is hot outside ")
    print("It is sunny")
elif temp<=0 and is_sunny:
    print("It is cold outside:")
    print("It is Sunny")
elif 28 > temp>0 and not is_sunny:
    print("It is warm outside")
    print("It is Cloudy")
elif temp <= 0 and not is_sunny:
    print("It is hot outside:")
    print("It is cloudy")
elif 28 > temp > 0 and not  not is_sunny:
    print("It is warm outside") #It is hot outside:
    print("It is Cloudy") #It is cloudy
#countdown time
import time
my_time = int(input("Enter the time in seconds:"))
for x in range(0,my_time):
    print(x)
    time.sleep(1)
print("Time's UP!") 
# Second option to count backward
import time
my_time = int(input("Enter the time in seconds:"))
for x in range (my_time,0,-1): # to count backward
    print(x)
    time.sleep(3)
print("Your time is over!")
# Third option 
import time
my_time = int(input("Enter your time in seconds:"))
for x in range(my_time,0,-1):
    seconds = x%60 #gives remeinder of any division
    print(f"00:00:{seconds:02}") #{seconds:02}= format specifier
    time.sleep(1)
print("Time's Up")
#shoping cart program
foods= []
prices=[]
total=0
while True:
    food= input("enter a food to buy(q to quit):")
    if food.lower()== "q":
        break
    else:
        price = float(input(f"enter the price of {food}: $"))
        food.append(food)
        price.append(price)  #2:42 doesn't work well '
print("----- YOUR CART----")

for food in foods:
    print(food, end= "")
    for price in prices:
        total += price
print(f" Your total is: ${total}")
# 2dlist =
fruits=            ["apple","orange","banana","coconut"]
vegetables=["celery","carrots","potatoes"]
meats=         ["chicken","fish","turkey"]
groceries = [fruits,vegetables,meats]
#print(groceries) #[['apple', 'orange', 'banana', 'coconut'], ['celery', 'carrots', 'potatos'], ['chicken', 'fish', 'turkey']]
print(groceries[0]) #['apple', 'orange', 'banana', 'coconut']
print(groceries[1])  #['celery', 'carrots', 'potatoes']
print(groceries[2])  #['chicken', 'fish', 'turkey']
print(groceries[0][0]) #apple first fruit from fruits
print(groceries[2][1]) #fish
groceries = [["apple","orange","banana","coconut"],
             ["celery","carrots","potatoes"],
             ["chicken","fish","turkey"]]
for collection in groceries:
    for food in collection:
        print(food,end = " ")
    print() #apple orange banana coconut 
            #celery carrots potatoes 
            #chicken fish turkey  #also ok to use ([]) or ({}) 
# Python quiz game
questions = (" How many elements in the periodic table?: ",
             " Which animal lays largest eggs?: ",
             " What is the most abundant gas in the Earth?: ",
             "How many bones in the human body?: ",
             "  Which planet in the solar system is the hottest?:")
options =(("A. 116", "B.117 ", "C.118 ","D.119 "),
          ("A.Whale", "B. Crocodile ", "C.Elephant ","D.Ostrich "),
          ("A. Nitrogen", "B.Oxygen ", "C.Carbon-Dioxide ","D.Hydrogen "),
          ("A.206", "B. 207", "C.208 ","D.209 "),
          ("A.Mercury", "B.Venus ", "C.Earth ","D.Mars "))
answers = ("C","D","A","A","B")
guesses= []
score= 0
question_num= 0

for question in questions:
    print( "---------------")
    print(question)
    for option in options[question_num]:
        print(option)
    guess = input("Enter(A,B,C,D): ").upper()
    guesses.append(guess)
    if guess == answers[question_num]:
        score +=1
        print("Correct")
    else:
        print("Incorrect")
        print(f'{answers[question_num]} is the correct answer')
    question_num+= 1
print( " ------------------")
print("   RESULT ")
print ("-------------------")

print("answers:" , end = " ")
for answer in answers:
    print(answer,end=" ")

print("guesses:" , end = " ")
for guess in guesses:
    print(guess,end=" ")
print()
score = int(score /len(questions) * 100)
print(f"Your score is {score}%") #answers: C D A A B guesses: A B A A B 
                                 #Your score is 60%
# dictionary
capitals = {"USA": "Washington D.C.",
            "India": "New Delhi",
            "China": "Beijing",
            "Russia": "Moscow"}
print(dir(capitals))
print(help(capitals))
print(capitals.get("USA")) #Washington D.C.
if capitals.get("Japan"):
    print("That capital exist ")
else:
    print("That capital doesn't exist") #That capital doesn't exist
if capitals.get("Russia"):
    print("That capital exist ")
else:
    print("That capital doesn't exist") #That capital exist
# Concession stand program using dictionary
menu = {"pizza": 3.00,
        "nachos":4.50,
        "popcorn":6.00,
        "fries": 2.50,
        "chips": 1.00,
        "pretzel": 3.50,
        "soda":3.00,
        "lemonade": 4.25}
cart  =[]
total = 0
print("----------MENU ")
for key,value in menu.items():
    print(f"{key:10}:${value:2f}")
print("-----------------------")

while True:
    food= input("Select an item(q to quit):").lower()
    if food == "q":
        break
    elif menu.get(food) is not None:
        cart.append(food)
print("---------YOUR ORDER-------")
for food in cart:
    total += total+menu.get(food)
    print(food,end = "  ")
print()
print(f"Total is:${total:2f}")
# IMPORT RANDOM
import random
#print(help(random))
number=random.randint(1,20)
print(number) #any number
import random
low =1
high = 100
number= random.randint(low,high)
number = random.random()
print(number) #0.47490640923597605
import random
low =1
high = 100
options = ("rock","paper","scissors")
options= random.choice(options)
print(options)
import random
low =1
high = 100
options = ("rock","paper","scissors")
cards = ["2","3","4","5","6","7","8","9","10","J","K","Q","A"]
random.shuffle(cards)
print(cards) #['K', '8', '5', '10', 'A', '2', 'Q', '3', '7', '6', '4', 'J', '9']
#NUMBER GUESSING GAME
import random

lowest_num=1
highest_num =100
answer = random.randint(lowest_num, highest_num)
print(answer) #51
guesses =0
is_running= True
print("Python Number Guessing Game")  #Python Number Guessing Game

print(f"Select a number between  {lowest_num} and {highest_num}")  #Select a number between  1 and 100

while is_running:
    guess= input("Enter your guess: ")
    if guess.isdigit():
        guess= int(guess)
        guesses+=1
        if guess<lowest_num or guess> highest_num:
            print("That number out of range")
            print(f"Please,select a number between {lowest_num} abd {highest_num}")
        elif  guess<answer:
            print("Too low!Try again!")
        elif guess>answer:
            print("Too high!Try again!")
        else:
            print(f"Correct! The answer was{answer}")
            print(f"NUmber of guesses:{guesses}")
            is_running = False
    else:
        print("Invalid guess")
        print(f"Please select a number between {lowest_num} and {highest_num}")
#Rock,paper,Scissors game
import random
options =("rock","paper","scissors")
running= True

while True:
    player =None
    computer= random.choice(options)

    while player not in options:  # to use only given options
        player = input("Enter a choice(rock,paper,scissors):")
    print(f"Player:{player}")
    print(f"Computer:{computer}")
    if player == computer:
        print("It's a tie!")
    elif player == "rock" and computer == "scissors":
        print("You win!")
    elif player == "paper" and computer == "rock":
        print("You win!")
    elif player == "scissors" and computer == "paper":
        print("You win!")
    else:
        print("You lose!")
    if not input("Play again? (y/n): ").lower()=="y":
        running= False
    print("Thanks for playing!")
# dice art
import random
# print("\u25CF \u250C \u2500 \u2510 \u2502 \u2514 \u2518")
# ● ┌ ─ ┐ │ └ ┘ #characters are needed to built a dice
''' 
"┌─────────┐" #9 times
"|         |"
"|         |"
"|         |"
"└─────────┘" '''
dice_art ={
    1:("┌─────────┐",
       "|         |",
       "|    ●    |",
       "|         |",
       "└─────────┘"),
    2:("┌─────────┐",
       "|  ●      |",
       "|         |",
       "|     ●   |",
       "└─────────┘"),
    3:("┌─────────┐",
       "|  ●      |",
       "|    ●    |",
       "|     ●   |",
       "└─────────┘"),
    4:("┌─────────┐",
       "|  ●   ●  |",
       "|         |",
       "|  ●   ●  |",
       "└─────────┘"),
    5: ("┌─────────┐",
        "|  ●   ●  |",
        "|    ●    |",
        "|  ●   ●  |",
        "└─────────┘"),
    6:("┌─────────┐",
       "|  ●   ●  |",
       "|  ●   ●  |",
       "|  ●   ●  |",
       "└─────────┘")
}
dice= []
total=0
num_of_dice = int(input("How many dice?: "))
# random.randint(1,6) #The randint function in Python is a powerful tool
# for generating random integers between two specified values.
# dice.append(random.randint(1,6))
for die in range(num_of_dice):
    dice.append(random. randint(1,6))
print(dice) # =>How many dice?: 5 =>[4, 2, 6, 1, 3]
# for die in range(num_of_dice):
#    for line in dice_art.get(dice[die]): #for every line
#        print(line)
for line in range(5):    # each tuple is made out of 5 elements, so 
                         #instead of printing horizontal line, so we need 
                         #to copy first lines of dice (1,3)
    for die in dice:
        print( dice_art.get(die)[line], end="")
    print()     #How many dice?: 3
                # [2, 1, 2]
                #┌─────────┐┌─────────┐┌─────────┐
                #|  ●      ||         ||  ●      |
                #|         ||    ●    ||         |
                #|     ●   ||         ||     ●   |
                #└─────────┘└─────────┘└─────────┘
                #total:5
for die in dice:
    total = sum(dice)  # if +=>TypeError: unsupported operand type(s) for 
                       # #+=: 'int' and 'list'
print(f"total:{total}") #total:13
# function = A block of reusable code
#            place() after the function name to invoke it
#print("Happy birthday to you!") # imagine that it's a song of your own
#print(" You are old!")          # and this song has to be repeated 3 times
#print("Happy birthday to you!")
#print()
def happy_birthday():
    print("Happy birthday to you!")
    print(" You are old!")
    print("Happy birthday to you!")
happy_birthday() # to invoke the func only once,
happy_birthday() #so to invoke it 3 times,
happy_birthday() #need to invoke it 3 times
# in case i wanna add smth new =>happy_birthday("Darling")
def happy_birthday(name,age):
    print(f"Happy birthday to {name}!")  #Happy birthday to Darling!
    print(f" You are {age}!")           # You are 20!
    print(f"Happy birthday to {name}!") #Happy birthday to Darling!
happy_birthday("Darling",20)
# displace_invoice
def display_invoice(username,amount,due_date):
    print(f"Hello {username}")
    print(f" Your bill of ${amount:.2f} is due {due_date}")

display_invoice(" Amelia", 55.60,"01/01") #Hello  Amelia
                                         #Your bill of $55.60 is due 01/01

#RETURN= statement used to end a function and
#         send a result back to the caller
def add(x,y):
    z =x+y
    return z
def subtract(x,y):
    z =x-y
    return z
def multiply(x,y):
    z =x * y
    return z
def divide(x,y):
    z =x / y
    return z
print(add(5,2))  #
print(subtract(5,2)) #3
print(multiply(5,2)) #10
print(divide(5,2)) #2.5
def create_name ( first,last):
    first = first.capitalize()
    last= last.capitalize()
    return first  + " " + last
full_name = create_name ("tom","hagen")
print(full_name) #Tom Hagen
#Задача 1. FizzBuzz
#Задача: Напишите программу, которая выводит числа от 1 до 100. Для чисел, кратных 3, выводите "Fizz", для чисел, кратных 5 — "Buzz",
# а для чисел, кратных 3 и 5 — "FizzBuzz".
'''for i in range(1,100):
    if i % 3 ==0 and i% 5==0:
        print("FizzBuzz")
    elif i % 3 ==0:
        print("Fizz")
    elif i %5 ==0:
        print("Buzz")
    else:
        print(i)'''
#for prof
'''def fizz_buzz():
    return[
        "FizzBuzz" if i %3 ==0 and i%5==0 else "Fizz" if i%3==0
        else" Buzz" if i %5==0 else
        i
        for i in range(1,100)
    ]
print ("\n".join(map(str,(fizz_buzz()))))'''
#Задача 2. АнаграммаюСлово или словосочетание, образованное путём перестановки букв, составляющих другое слово (или словосочетание).

#Задача: Напишите функцию, которая проверяет, являются ли две строки анаграммами.

'''def is_anagram (str1,str2):
    return sorted(str1)==sorted(str2)
print(is_anagram("Stop", "Post")) #False
print(is_anagram("stop","post")) #True
print(is_anagram(" Hello", "Sam"))''' #False

'''from collections import Counter

def is_anagram(str1,str2):
    return Counter(str1)== Counter(str2)
print(is_anagram(" tom","mot"))
print(is_anagram ("hello"," world"))'''
#Задача 3. Частотный словарь
#Напишите функцию, которая подсчитывает количество каждого символа в строке.
'''def char_frequency(s):
    frequency ={}
    for char in s:
        if char in frequency:
            frequency[char] +=1
        else:
            frequency[char] =1
    return frequency
print(char_frequency("Einstein"))''' #{'E': 1, 'i': 2, 'n': 2, 's': 1, 't': 1, 'e': 1}
'''from collections import Counter


def char_frequency(s): #count the number of characters (character frequency) in a string.
    return dict(Counter(s))
print(char_frequency("Einstein"))''' #{'E': 1, 'i': 2, 'n': 2, 's': 1, 't': 1, 'e': 1}
#Задача 4. Поиск максимального подмассива (Алгоритм Кадане)
# Реализуйте алгоритм Кадане для нахождения подмассива с максимальной суммой.
'''def max_subarray_sum(arr):     # run two nested loops to iterate over all possible subarrays and
                               # find the maximum sum
    max_sum = current_sum =arr[0]
    for num in arr [1:]:
        current_sum = max(num,current_sum+num)
    return max_sum
print(max_subarray_sum([-2,1,-3,4,-1,2,1,-5,4]))'''#-2
#Задача 5. Ротация списка
#Задача: Реализуйте функцию, которая циклически сдвигает список на k позиций.
# A deque stands for Double-Ended Queue. It is a data structure that allows adding and
# removing elements from both ends efficiently.

from collections import deque
def rotate_list(lst,k):
    d =deque(lst)
    d.rotate(k) #Метод rotate(k) позволяет легко выполнить циклический сдвиг списка на k позиций.
    return(list(d))
print(rotate_list([1,2,3,4,5],2))  #[4, 5, 1, 2, 3]
#OOP- info for IT  as text and info(pic)
#переменная внутри класса= поле класс, класс-  для удобства внесения данных
'''class Animals:
    name = None
    age = None
    color = None

Animals.age = 4
Animals.color = "Black"
Animals.price = 1000.0
print(Animals.age)''' #4
'''class Car_BMW:
    brand = None
    color = None   #NOT GOOD CODE
    price = None
brand_car= Car_BMW.brand= "BMW"
color_brand= Car_BMW.color  ="Blue"
price_car= Car_BMW.price = 10.000
print(brand_car,color_brand,price_car) #BMW Blue 10.0

brand_car= Car_BMW.brand= "Mers"
color_brand= Car_BMW.color  ="Black"
price_car= Car_BMW.price = 15.000
print(brand_car,color_brand,price_car)''' #Mers Black 15.0
'''class Car:
    def __init__(self,brand,color,price):
        self.brand = brand
        self.color = color
        self.price= price
    def show_info(self):
        return f'car:{self.brand},color:{self.color},price:{self.price}'
car1= Car('BMW','Red', '12.000')
car2 = Car('Mers','Blue','15.000')
print(car1.show_info()) #car:BMW,color:Red,price:12.000

print(car2.show_info()) #car:Mers,color:Blue,price:15.000'''
#Полиморфизм
'''class Person:
    def __init__(self,age,sex):  #self- относится только к полям данного поля , тк отл. внешний и внутренний
        self.age = age
        self.sex = sex
    def show_info(self):   #get_data
        return f'Person:{self.age},sex:{self.sex}'
person1 = Person('20','male')
person2 =Person('50','women')
print(person1.show_info()) #person:20,sex:male

print(person2.show_info())''' #person:50,sex:women

'''class Phone:
    def __init__(self,brand,color,price,memory):
        self.brand = brand
        self.color= color
        self.price= price
        self.memory =  memory
    def show_info(self):
        return f'Phone:{self.brand},color:{self.color},price:{self.price},memory:{self.memory}'
phone1 = Phone('Apple','Silver','11.000','1T') #Phone:Apple,color:Silver,price:11.000,memory:1T

phone2 = Phone('Samsung','Black','12.000','1.5T') #Phone:Samsung,color:Black,price:12.000,memory:1.5T

print(phone1.show_info())
print(phone2.show_info())'''
#описать робота за счет
'''class Cat:
    name= None
    age = None
    isHappy= None

#cat1= Cat('Alenka','2','happy')
cat1=Cat()
cat1.name = 'Alenka'
cat1.age= 2
cat1.isHappy= True
cat2=Cat()
cat2.name = 'Sakura'
cat2.age=1
cat2.isHappy= False
print(cat1.name)
print(cat2.name)'''
#2
class Cat:
    name= None
    age = None
    isHappy= None
    def set_data(self,name,age,isHappy):
        self.name = name
        self.age= age
        self.isHappy= isHappy
cat1=Cat
cat1.set_data('Alenka',2,True)
cat2=Cat
cat2.set_data('Sakura',1,False)
#POLIMIRFISM- Greek word...-"to have many forms".
#              Poly= Many;Morphy=form
# 2 wats to achieve POlYMORPHISM
# 1. INHERITANCE = An object could be treated of the same class as a parent class
# 2."Duck typing"= Object must have necessary attributes/methods

from abc import ABC,abstractmethod
class Shape:
    @abstractmethod
    def area(self):
        pass

class Circle(Shape):
    def __init__(self,radius):
        self.radius= radius
        return (3.14 * self.radius ** 2)  # to calculate area in the circle

class Square(Shape):
    def __init__(self,side):
        self.side=side
    def area (self):
        return self.side ** 2
class Triangle (Shape):
    def __init__(self,base,height):
        self.base= base
        self.height= height
    def area(self):
        return self.base* self.height * 0.5


#circle = Circle()
#create a list of shapes
class Pizza(Circle):
    def ___init__(self,topping, radius):
        super().__init__(radius)
        self.topping= topping
        self.radius= radius



shapes = [Circle (4),Square(5),Triangle(6,7),Pizza("pepperoni",15)]
for shape in shapes:
    print(f"{shape.area()} cm")
#Methods
class Microwave:
    def __init(self,brand:str,power_rating:str)->None:
        self.brand= brand
        self.power_rating= power_rating
        self.turned_on: bool= False

    def turn_on(self)->None:
        if self.turned_on:
            print(f' Microwave ({self.brand} is already turned on')
        else:
            self.turned_on = True
            print(f'Microwave{self.brand } is now turned on')
    def turn_off(self)->None:
        if self.turned_on:
            self.turned_on= False
            print(f' Microwave ({self.brand} is now  turned off')
        else:
            print(f'Microwave{self.brand } is already turned off')
    def run(self,seconds:int)->None:
        if self.turned_on:
            print(f'Running {self.brand} for {seconds} seconds')
        else:
            print(f'A mystical force whispers:"Turn on your microwave first...')


smeg: Microwave = Microwave ('Smeg','B')

class Camera:
    def  get_data(self,__memory,__photos):
        self.memory= memory
        self.photos = photos
    def take_photos(self):
        if self.memory>10:
            self.photos += 'очередная новая фотка'
            self.memory -=10
            return 'Photo is taken'
        else:
            return ' Not enough memory'
 class Animals:  #базовый класс .родительский
    def __init__(self,species,age,color,breed):
        self.species =species
        self.age= age
        self.color =color
        self.breed =breed
    def get_all_info(self):
        return f'
                Species: {self.species}
                Age: {self.age}
                Color:{self.color}
                breed :{self.breed}'           
class Dog:
    def __init__(self,color,age,breed):
        self.color= color
        self.age= age
        self.breed= breed
    def gaph (self):
        print(f' Gaph, I am {self.color} and {self.age}',{self.breed})
dog =Dog( 'black',3,'pet')
dog1 = Dog('white',4,'pet')
dog2 =Dog('orange','1','wild')
dog.gaph() #Gaph, I am black and 3

dog1.gaph() # Gaph, I am white and 4
dog2.gaph() Gaph, I am orange and 1 {'wild'}
 class Cat:
    def __init__(self,name,age):
        self.name= name
        self.age=age
    def meow (self):
        print(f'Meow, My name is {self.name}')

cat = Cat('Alenka',2)
cat.meow()         
class Animals_on_land(Animals):  #идет расширение от родительского
    def set_data(self, species,age,color,breed,habitat):#тут указываем дополнительные поля
        super(Animals,self).__init__(self,species,age,color,breed) # переопределяем , расширяем
        self.habitat= habitat

    def get_all_info(self):  #является полиморфизмом, переопределяем и можем по-лругому переотпределять
        all_info = super().get_all_info()
        return f'{all_info} Место обитания: {self.habitat}'
animal_on_land = Animals_on_land('Хишник',2,'yellow','Cat')
animal_on_land.habitat = 'Africa'
print(animal_on_land.get_all_info())'''   #   Species: Хишник
#                Age: 2
 #               Color:yellow
#                breed :Cat
Создать базовый класс Animals(type, speed, location).Умеют передвигаться

Создать класс Cat().Умеет бегать.Просит накормить

Создать класс Shark().Умеет плавать.Охотиться на всех вокруг 

Создать класс Turtle().Умеет ползать
'''

class Animals:
    def init(self, type, speed, location):
        self.type = type
        self.speed = speed
        self.location = location

    def move(self, a, b):
        self.a = a
        self.b = b
        return f'{self.a} -> {self.b}'

    def eats(self, food):
        self.food = food
        return self.food


class Cat(Animals):
    def init(self, type, speed, location):
        super().init(type, speed, location)

    def move(self, a, b):
        super().move(a, b)
        return f'{self.location} - {self.a} -> {self.b}'

    def eats(self, food):
        super().eats(food)
        return 'Накорми меня вот этим:', self.food

    def str(self):
        info_move = self.move(self.a, self.b)
        info_eats = self.eats(self.food)
        return f'''
                    Передвигается - {info_move}, 
                    Кушает - {info_eats}'''
''' 
class Shark(Animals):
    def init(self, type, speed, location):
        super().init(type, speed, location)

    def move(self, a, b, tail):
        super().move(a, b)
        self.tail = tail
        return f'{self.tail} - {self.a} -> {self.b}'

    def eats(self, food):
        super().eats(food)
        return 'Сегодня охота на', self.food

    def get_all_info(self):
        info_move = self.move(self.a, self.b, self.tail)
        info_eats = self.eats(self.food)
        return f'''
                    Передвигается - {info_move},
                    Кушает - {info_eats}'''


cat1 = Cat('Cat', '40km', 'Home')
cat1.move('room1', 'room2')
cat1.eats('Fodder')

print(cat1)

shark1 = Shark('Рыба', '150km', 'Ocean')
shark1.move('Ocean1', 'Ocean2', True)
shark1.eats('Fish')

print(shark1.get_all_info())
class Potion:
    def init(self, size, price):
        self.size = size
        self.price = price

    def drink(self, character):
        pass


class Character:
    def init(self, hp, mana, lvl):
        self.hp = hp
        self.mana = mana
        self.lvl = lvl

    def go(self):
        return 'Бегает определенным образом'

    def fight(self):
        return 'Умеет сражаться'

    def drink(self, character):
        self.character = character
        return f'Пьет персонаж: {self.character}'


class Goblin(Character):
    def atributes(self, hp, mana, lvl, trick):
        super().init(hp, mana, lvl)
        self.trick = trick

    def go(self):
        return 'Бегает очень быстро'

    def fight(self):
        return 'Не очень то умеет сражаться, но хитрый :)'

    def drink(self, character):
        super().drink(character)
        self.hp += 10
        return 'Здоровье увеличена на 10hp'


class Zombie(Character):
    def atributes(self, hp, mana, lvl, smart):
        super().init(hp, mana, lvl)
        self.smart = smart

    def go(self):
        return 'Бегает очень медленно'

    def fight(self):
        return 'Очень то умеет сражаться, еще и умный :)'

    def drink(self, character):
        super().drink(character)
        self.hp += 5
        return 'Здоровье увеличена на 5hp'
