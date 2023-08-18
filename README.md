#INDEXING AND SLICING
text = "i love india"
text[0]
Out[4]:
'i'
In [3]:
 
text[2:]
Out[3]:
'love india'
In [5]:
xxxxxxxxxx
 
text[:5]
Out[5]:
'i lov'
In [6]:
xxxxxxxxxx
 
text[::-1]
Out[6]:
'aidni evol i'
In [7]:
x
list = ["sai","kiran","nani","hari"]
print(list)
type(list)
['sai', 'kiran', 'nani', 'hari']
Out[7]:
list
In [ ]:
x
​
In [18]:
 
marks = [45,55,32,36,47,55,52]
marks.sort()
print(marks)
[32, 36, 45, 47, 52, 55, 55]
In [21]:
 
print(55 in marks)
True
In [22]:
xxxxxxxxxx
 
print("sai" in list)
True
In [23]:
 
for names in list:
    print(list)
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
['sai', 'kiran', 'nani', 'hari']
In [24]:
xxxxxxxxxx
len(marks)
Out[24]:
7
In [27]:
x
marks = [45,55,32,36,47,55,52]
max(marks)
Out[27]:
55
In [28]:
xxxxxxxxxx
 
marks = [45,55,32,36,47,55,52]
min(marks)
Out[28]:
32
In [29]:
 
list = ["sai","kiran","nani","hari"]
list.clear()
list
Out[29]:
[]
In [33]:
xxxxxxxxxx
list = ["sai","kiran","nani","hari"]
list.insert(2,"appu")
print(list)
['sai', 'kiran', 'appu', 'nani', 'hari']
In [35]:
x
list = ["sai","kiran","nani","hari"]
list.reverse()
print(list)
['hari', 'nani', 'kiran', 'sai']
In [36]:
​
  Cell In[36], line 3
    print(true)
    ^
IndentationError: expected an indented block after 'if' statement on line 2


In [37]:
x
list = ["sai","kiran","nani","hari"]
hai = ["vani","krishna"]
list.extend(hai)
print(list)
['sai', 'kiran', 'nani', 'hari', 'vani', 'krishna']
In [39]:
xxxxxxxxxx
 
list = ["sai","kiran","nani","hari"]
list.index("hari")
Out[39]:
3
In [40]:
xxxxxxxxxx
 
list = ["sai","kiran","nani","hari"]
list.pop(1)
Out[40]:
'kiran'
In [43]:
list = ["sai","kiran","nani","hari"]
list.reverse()
list
Out[43]:
['hari', 'nani', 'kiran', 'sai']
In [ ]:
​
