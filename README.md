#----------------#-------------------#--------------------#-------------------#-------------------#----------------

# Arithmetic Operators:- + (Addition),  - (Subtraction), * (Multiplication), / (Division) , % (Modulus - returns the remainder of a division) // (Floor Division) ** (Exponentiation) print(2**5) 2 ki power 
# Assignment Operators:-  = (Assignment) += (Addition assignment) -= (Subtraction assignment) *= (Multiplication assignment) /= (Division assignment) %= (Modulus assignment) //= (Floor division assignment) **= (Exponentiation assignment)

# Comparison (Relational) Operators:- == (Equal to) != (Not equal to) < (Less than) > (Greater than) <= (Less than or equal to), >= (Greater than or equal to)

# Logical Operators:- and (Logical AND) or (Logical OR) not (Logical NOT)

# Membership Operators:-  in (True if a value is found in the sequence) not in (True if a value is not found in the sequence)

# Bitwise Operators:-  & (Bitwise AND)| (Bitwise OR) ^ (Bitwise XOR) ~ (Bitwise NOT) << (Left shift) >> (Right shift)

1️⃣ AND Operator (and)
👉 Dono condition True hongi tabhi result True aayega.
👉 Ek bhi False hua to result False.

| Condition       | Result  |
| --------------- | ------- |
| True and True   | ✅ True  |
| True and False  | ❌ False |
| False and True  | ❌ False |
| False and False | ❌ False |

2️⃣ OR Operator (or)
👉 Ek bhi True hua to result True aayega.
👉 Dono False honge tabhi False.

| Condition      | Result  |
| -------------- | ------- |
| True or True   | ✅ True  |
| True or False  | ✅ True  |
| False or True  | ✅ True  |
| False or False | ❌ False |


3️⃣ NOT Operator (not)
👉 Ye result ko ulta kar deta hai.

| Condition | Result  |
| --------- | ------- |
| not True  | ❌ False |
| not False | ✅ True  |




# Bitwise operator:-  har ek individual bit ke uper operation ko perform karna 
| Operator | Meaning               |                  |
| -------- | --------------------- | ---------------- |
| &        | Dono 1 ho tab 1       |                  |
|          |                       | Ek bhi 1 ho to 1 |
| ^        | Different ho to 1     |                  |
| ~        | Reverse bits          |                  |
| <<       | Multiply by 2 power n |                  |
| >>       | Divide by 2 power n   |                  |


1️⃣ Decimal Number System (Base 10)
👉 Ye normal numbers hote hain jo hum daily use karte hain.
👉 Isme digits hote hain: 0 se 9


 2️⃣ Binary Number System (Base 2)
👉 Isme sirf 0 aur 1 hote hain.
👉 Computer binary me kaam karta hai.

3️⃣ Octal Number System (Base 8)
👉 Isme digits hote hain: 0 se 7


| Type    | Base | Digits |
| ------- | ---- | ------ |
| Decimal | 10   | 0–9    |
| Binary  | 2    | 0–1    |
| Octal   | 8    | 0–7    |


# Identifiers:- python me identifier name hai jisse hum identifie karte hai jese variable ko,function ko,class ko,module or any other object. Us name ko identifier kehte hai 
Python me identifier(variable) rakhne ke kuch rules hote hai:
# 1.Letter ya underscore se start hona chahiye:- 
name = "Sanket"
_age = 25
1name = "Sanket"   # number se start nahi kar sakte ❌
# 2️⃣Beech me number aa sakta hai:- 
student1 = "Rahul"
# 3️⃣ Special symbols allowed nahi hai ❌  like !, @, #, $, and so on.
user-name = "Sanket"   # hyphen allowed nahi
# 4️⃣ Keywords use nahi kar sakte ❌
class = "Python"   # galat
# 5 Whitespaces are not allowed. ❌
Example First name 

Valid Examples:
---------------
variable_name
_internal_variable
myFunction
Class_Name
module_name


Invalid Examples:
-----------------
3variable (starts with a digit)
my-variable (contains a hyphen)
if (uses a reserved keyword)
class (uses a reserved keyword)

Conventions:- naam likhne ka style.

🔹 1️⃣ Pascal Case
👉 Isme har word ka first letter capital hota hai

🔹 2️⃣ Camel Case
👉 Isme first word small,
baaki words ka first letter Capital hota hai.

🔹 3️⃣ Snake Case
👉 Isme sab small letters
aur words ke beech me underscore _ hota hai. 

# variables:- python me variable ek name hai jo ki store karta hai value ko memory me in other languages Python is dynamically typed language hai, isliye variable kaa data type declare karne ki zarurat nahi hoti. Python khud runtime par type decide kar leta hai.

# A variable in Python is a name that refers to a value stored in memory.Python dynamically typed language hai, isliye variable kaa data type declare karne ki zarurat nahi hoti. Python khud runtime par type decide kar leta hai.


# keywords:- Python me Keywords woh special reserved words hote hain jo Python language me already defined hote hain aur unka specific meaning hota hai.Inhe hum variable name, function name, ya kisi aur identifier ke naam ke liye use nahi kar sakte.
Example =  if = 10   # ❌ Error aayega

:- id,else, elif,not,true,false,continue,def,try,except,lambda,import,or,pass,return ye sare 
datatypes:- 


# conditional statments:-  
✅ 1️ Simple `if` Statement:- 👉 Jab condition True ho tab code chalega.
✅ 2 `if-else` Statement:- 👉 True ho toh `if` chalega, warna `else`.
✅ 3 `if-elif-else` (Else If Ladder):- 👉 Multiple conditions check karne ke liye.
✅ 4 Nested if Statement:- 👉 Jab ek `if` ke andar doosra `if` ho. and woh sequentially work karege jab outer if condtion true hogi tabhi inner if execute hoga 
✅ 5 Ternary Operator (Conditional Expression):- One line me if-else
Example:- result = "Pass" if marks >= 40 else "Fail"
✅ 6️⃣  Logical Operators (Conditions ke andar use hote hain)
| Operator | Meaning             |
| -------- | ------------------- |
| `and`    | Dono condition True |
| `or`     | Ek bhi True         |
| `not`    | Condition reverse   |

✅ 7️⃣  Switch Statement (Python me direct switch nahi hota ❌)
python me traditional `switch` nahi hota.
🔹 Lekin Python 3.10+ me **match-case** aaya hai:
✔ Isko Python ka **switch replacement** bol sakte hain.

✅ `if-elif-else` Ladder Kya Hai?

Python me **"if-elif-else" ladder** ek series of conditional statements hoti hai jo **complex decision making** ke liye use ki jati hai.

Yeh humein multiple conditions ko **ek ke baad ek check karne** ki suvidha deti hai aur jis condition ka result True hota hai, uska code execute ho jata hai.


# what is module:- it's file contaning statments jiske under multiple classes then functions variables unki collections iss tarike se store ki huvi hoti hai Taaki hume Advantages mile sake joo kaam same kare usko sath me daal sake Ex:- math ,random ,time,datetime

module :- math,time,random,datetime,copy,decimal,json,,os,sys,therading,zipfile,uuid

pakages:- collection of module file Ex:- pygame,Django RESt framwork,FastAPi,celery,scrapy,beautiful soap 

Library:- Numpay,pandas,requests,pillow,pytest,slenuim,tensaflow

Built-in functions:- map(),filter,reduce,min,max,len,input,print,sorted

User-defined Functions:- 

Attribute :- variable jo class ya object ke andar hota hai.
what is methods :- (class ke under jo function aata hai woh this is none as methods)
what is instance:-(constrocter ke under jo variable ata hai woh)

# self hai isko hum object bhi keh sakte hai woh humara object hi huva 
Ex:- Object ke liye → Instance Attribute (self.name)
Class ke liye → Class Attribute / Static Variable (school)

# static variable*:- Ye class ke andar define hota hai (methods ke bahar yaani func ke bhar).Python me isko Class Attribute bhi kehte hain.
Ex:- class comapny:
    comany_name = "Wipro" # **static variable 

    def __init__(self,employe_name):
        self.employee_name = employe_name

# instance method:- methods ke under implemetation karte hai instance variable kaa use karke to ese methods ko instance method kaha jata hai 

# instance variables :- inside a constorctorce variable this instance  non as (object ke level variable yaa ni object to object value of varid)

# static variable :- inside a class we can declare this is static varable(class Level)

# Local variable :- ye hamare function ke baad decalare karte hai (method Level variable)

# global:-out side of class we can define this variable 


# 1. what is function 2. what is python keywords and wat are the keywords 3. what are global variables and local variables 4.what is type con ersion in python?   

# data-collection:- 

# dict:- python ke under dictionary built in data type hai jo ki use hota hai key and value pair me jo ikha jata hai Curly braces {} me and woh mutable hai jisme key hai woh humari unique hoti hai And value mutable hoti hai dictionary hai woh unnorderd,Unindexed,duplicate values are not allowed 
# methods:- get,key,value,update,items,clear,copy, pop,popitems,fromkeys,setdefault

# setdefault:- Sir, setdefault() dictionary method hai jo kisi key ko check karta hai. Agar key exist karti hai to uski value return karta hai. Agar nahi karti to default value ke saath dictionary me add kar deta hai

# List:- orderd,mutable,indexing,slicing,duplicate values are allowed 
python me list data structure hai jo use hota hai collection of items ko store karne ke liye list likhi jaati hai [] square bracket me and ye  orderd hai and mutable hai matlab runtime pe insert update delete karva sakte hai 
slicing me formula hai start+stop+step  <--- step yaa ni tumhe utne steps jump karne hai -revse side and pluse hoi to 0 (zero) se  start 0,1,2,3,4,5,etc (minus) -1,-2,-3,-4,-5 etc 

append:-  end of the list single element ko add kar sakte hai 
extend:-  end of the list multiples elements add hote hai tod ke add karta hai 

for knowldge 
Ager extend me hum 'chilli' or ('chilli') isko extend se karayenge to  'c', 'h', 'i', 'l', 'l', 'i' is tarah se aayega kyu ki woh string hai and tuple me hai isliye usse tod dega each itrable me and either woh [chilli] list me 
tro out put aayega :- ['tomato', 'potato', 'onion', 'chilli']


🔥 Ek Important Interview Trick

Agar interviewer bole:

a = ['python']
a.extend('swift')
print(a)

Tum confidently bolo: Kyuki string iterable hoti hai.

['python','s','w','i','f','t']

# dict:-  pop:- dict me Dictionary Key dena compulsory hai usko remove karta hai 
# dict:-  popietms :-  popitems hamesha dict last keyvalue pair ko remove karta hai usme arguments nahi pass kar sakte woh automatically last key value pair ko hi remove karta  hai 
# list kaa pop:- Default last element remove karta hai
# set pop:- pop() random element remove karta hai
# list remove:- woh value ke basis pe delete karta hai naa ki index ke basis pe 
Ex:- ['a','b','c'].remove('b')   # value 'b' remove karega ✅
['a','b','c'].remove(1) Python value 1 dhoondega ❌ Index 1 nahi dhoondega
# list in:- sort()  # assendig order me karta hai value ko yaani ABCD  sahi karta hai 123456 wise assending me 
Example and isme captial letters first aate hai Ex:- 'B' (66),'Z' (90),'a' (97)
a = ['Zebra', 'apple', 'Banana']
a.sort()
print(a)
# Answer:- ['Banana', 'Zebra', 'apple']
# set:- unorded,unindexed,duplicate values are not allowed or set indexing support nahi karta ❌
1️⃣ Set me duplicate values allow nahi hoti:- {1,2,3,4,5,6,1,2,4,7}
Actually banega:- {1,2,3,4,5,6,7} :- Duplicate 1,2,4 remove ho jayenge automatically.
# frozen set:- immutable hota hai isme changes nahi kar sakte hum 
| Feature  | set   | frozenset |
| -------- | ----- | --------- |
| Mutable  | ✅ Yes | ❌ No      |
| add()    | ✅     | ❌         |
| remove() | ✅     | ❌         |
| Hashable | ❌     | ✅         |
# Normal set hashable nahi hota,Isliye set ko dictionary key nahi bana sakte.
# Lekin frozenset hashable hota hai ✅ Isliye use dictionary key bana sakte ho.

# Tuple : ordered, immutable, indexing, slicing, duplicate values are allowed 

1️⃣ Positional Parameter:- Ye order ke basis par values leta hai.Position change karoge to result change ho sakta hai.
Ex:- 
def add(a, b):
    print(a + b)
add(5, 10)

Yaha:
5 → a
10 → b
Output:
15

2️⃣ Default Parameter:- Agar argument pass nahi kiya gaya to default value use hogi.

3️⃣ Keyword Parameter:- 👉 Jab function call karte waqt parameter ka naam use karte hain.
Ex:-  Yaha order matter nahi karta.
def intro(name, age):
    print(name, age)
intro(age=22, name="Sanket")

Output:Sanket 22

4️⃣ Variable Length Parameter:- 👉 Jab hume nahi pata kitne arguments aayenge.
(a) *args → Multiple Positional Arguments
(b) **kwargs → Multiple Keyword Arguments

# *for loop:- Jab hume pata ho kitni baar repeat karna hai. 
# For loop ka use tab karte hain jab hume fixed number of iterations karni hoti hain ya kisi sequence jaise (list, tuple, string ya dictionary) par iterate karna ke liye hota hai

# while loop:- Jab tak condition true rahe tab tak chalega.
# while loop condition based hota hai.While loop tab use hota hai jab tak ek condition true rehti hai. Jab condition false ho jaati hai tab loop stop ho jaata hai. Isme iterations ka exact count pehle se pata hona zaroori nahi hota

# short diffrence:- For loop fixed iterations ke liye use hota hai, jabki while loop condition based hota hai
