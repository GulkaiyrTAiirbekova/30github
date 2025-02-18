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

    
  

