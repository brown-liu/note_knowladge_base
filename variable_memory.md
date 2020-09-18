###in python
a=1
b=a
b will output 1
and if a=10
b will still out put 10

however, this is different when hanlding list or dict.
a=[1,2,3,4,5]
b=a
a.append(10)
a will be [1,2,3,4,5,10]
and be will be updated too.  same to dictionart

this means a and b, when assigined to be the var for list or dict.
a and b will be the pointer, not just a simple variable.
can use b = a.copy() to simple pass the value. however, this will create a new memory in heap.

###in c++
int a =10;
int a=b;
above will do the same as in python.

if want to link
int &b=a;

create variable in heap
int * array =new int[]
array.delete()
