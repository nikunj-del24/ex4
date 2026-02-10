# ex4
NIKUNJ DEEP UPADHYAY
25070123081
ENTC B1

THEORY-
Set consist of various data stored in a variables in a curly braces.
We can check whether a given data is in set or not by using data name in set using print function which will result in true or false.
We can add certain data to a set and also can remove data from the set.
We can take the union from two sets by using union function. So the elements will be coming of both the sets. 
We can have a set in a tuple.
We can change the list into the tuple.
We can find the common data from the two or three sets using the & function.
We can subtract the common element from the two set.
We can use the discard function to remove any data from the set.

ALGORITHM-
Various types of data can be stored in a set.
a={"m","n","o","p",1,4,5}
We can check whether a data is present in a list using in function.
print("o" in a) which gives output as true
print("Shahrukh" in a ) which gives output as false.
we can remove any data from the set by using remove function.
a.remove(1)
print(a) will result a={"m","n","o","p",4,5}
We can take the union of two sets by using union function.
a={3,4,6}
b={2,5,6}
print("Union:") will result {2,3,4,5,6}
List can change into tuple.
e=[8,9,4,3,2]
f=set(e)
print(f) will result {2,3,4,8,9}
& function can be used to take common data from two or more sets
t={2,6,1,9}
s={5,6,7,8}
qh=s & t
print(qh) will result 6
we can subtract two set to not get common elements.
t={2,6,1,9}
s={5,6,7,8}
fd=s-t
print(fd) will result {5,7,8}
We can remove data from the set using discard function.
t={2,6,1,9}
t.discard("1")
print(t) will result {2,6,9}





