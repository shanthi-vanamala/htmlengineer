**1.what is a data type in python?**

A.In python, a data type is a classification that specifies the kind of value a variable can hold.it dictates how the data is stored in memory and operations can be performed on it.Every value in python is an object,and its data type is defined by the class to which it belongs.python is a dynamically typed language.meaning that it doesn't explicitly declare the data type of a variable when you create it.instead,python infers the data type based on the value assigned to the variable.



**2.List all the data type that we have in python?**

A.Numerator data type:integer,float,compl
 Sequence data type :string,tuple,list,range

 Boolean datatype

 Dictionary datatype

Set datatype

 Frozenset datatype

 None datatype



**3.what is the difference between mutable and immutable data types?**

A.MUTABLE:

   The value or content of a mutable object can be modified in place after its creation without creating a new object.

IMMUTABLE:

    we cannot change the value once it is defined if we want to change then we have create another object or reassign the values.



**4.what is the difference between int,float,and complex?**

A.int,float,complex are the numeric datatypes where integer refers the value of integer value without decimal and float refers the integer value with decimal point numbers and complex has two parts real parts and imaginary part.



**5.which data type is used to represent text in python?**

A.string data type is used for the text representation.



**6.what is the output of types(521)and type("521")?**

A.print(type(521))

print(type("521"))
 output:<class 'int'>
        <class 'str'>



**7.what is the difference between list,tuple,and set?**

A.lists and sets are mutable datatypes that we can change,lists are collection of ordered elements that contain the same elements and sets are unordered elements that do not contain the same elements.Tuples are immutable datatype that cannot change it also contain the same elements.



**8.How is a dictionary different from a list?**

A.list stores item in an ordered sequence,accessed by their numerical index,while the dictionaries stores the items with key-value pairs,accessed by their unique keys.



**9.what is the default data type of a number with a decimal point?**

A.In python,when we write a number with a decimal point like 2.14 or 4.0 its automatically treated as afloat,which is pythons default decimal/real number type.



**10.Declare variables of type int,float,string,and complex.**

A.A=56

 B=4.2

 C="Hi"

 D=2+3j



**11.Take any 3 datatypes examples and check type of each variable using the type() function.**

**A.a=5
     b=8.7

 c="hi"

 print(type(a))

 print(type(b))

 print(type(c))

 output:<class 'int'>

       <class 'float>

       <class 'sr'>



1**2.what happens if you try to add a string and an integer?**

A.if you try to add(concatentanate) a string and an integer in python using the+ operator-like this.

 operator-like this:

 'age'=+20

 it will raise a Type Error.

 TypeError can only cancatenate str(not "int")to str

 python is strongly typed and won't automatically convert the integer to a string.



**13.what is the output of:**

 1.x=\[1,2,3]

 2.y=(1,2,3)

 3.z={1,2,3}

 4.print(type(x),type(y),type(z))

A.x=\[1,2,3]

y=(1,2,3)

 z={1,2,3}

 print(type(x))

 print(type(y))

print(type(z))

output:<class 'list'>

       <class 'tuple'>

         **<class 'set'>**



**14.can you change a value in a tuple once it is defined?why or why not?**

A.it is not possible to change the value in the tuple,because tuple is a immutable datatype that means once it is defined the value cannot be changed. if we attempt to change the value ,it will raise the type error.



15.is reassignment possible for immutable datatype?**

A.it is possible to reassign the value in immutable datatypes,beacuse of datatype will not support changing values once defined but it allows you to reassignment of the values and creating the new object reassignment means we are not changing the existing value,it create a new object then the variable take the changed value after reassigning.





















































