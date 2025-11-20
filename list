List operations and methods  : 

my_list = ['p','r','o','g','r','a','m','m','e']  
print(my_list[2:5])  
print(my_list[5:])  
print(my_list[:])  
list1 = [10, 15, 11, 65, 30]  
list1.insert(1,80)  
print('INSERTED ELEMENT IN THE LISTS  :', list1)  
list1.sort()  
print('SORTED ELEMENT IN THE LIST IS :', list1) 
list1.reverse()  
print('REVERSED ELEMENT IN THE LIST IS :',list1.pop(3,)  
print('REMOVED ELEMENT IN THE LIST IS :', list1)  
print('LARGEST ELEMENT IN THE LIST IS :',max(list1))  
print('SMALLEST ELEMENT IN THE LIST IS :', min(list1))  

Output  
['o', 'g', 'r']  
['a', 'm', 'm', 'e']  
['p', 'r', 'o', 'g', 'r', 'a', 'm', 'm', 'e']  
INSERTED ELEMENT IN THE LIST IS : [10, 
80, 15, 11, 65, 30] SORTED ELEMENT IN 
THE LIST IS : [10, 11, 15, 30, 65, 80] 
REVERSED ELEMENT IN THE LIST IS : 
[80, 65, 30, 15, 11, 10] REMOVED ELEMENT 
IN THE LIST IS : [80, 65, 30, 11, 10] 
LARGEST ELEMENT IN THE LIST IS : 80  
SMALLEST ELEMENT IN THE LIST IS : 10  
—---------------------------------- 

List Comprehension  

fruits = ["apple", "banana", "cherry", "kiwi", "mango"] 
newlist = [] 
for x in fruits: 
if "a" in x: 
newlist.append(x) 
print(newlist) 
**************        
or ******************* 
fruits = ["apple", "banana", "cherry", "kiwi", "mango"] 
newlist = [x for x in fruits if "a" in x] 
print(newlist) 

output: ['apple', 'banana', 'mango']
—-------------------------------------------------------------- 
List Program :  

prices = [1.09, 23.56, 57.84, 4.56, 6.78] 
TAX_RATE = .08 
def get_price_with_tax(price): 
return price * (1 + TAX_RATE) 
final_prices = map(get_price_with_tax, prices) 
print( final_prices) 

Output :  
[1.1772000000000002, 25.4448, 62.467200000000005, 4.9248, 
7.322400000000001] 
—------------------------------------------------------------------------- 
Display the frequency of each element  in list  
l=[13,4,5,3,4] 
l1=[]  # 2,2 , 1 
l2=[]  # 3  4   5 
print("Element \t \t frequency") 
for i in l: 
if i not in l2: 
x=l.count(i)  # i= 3 
l1.append(x) 
l2.append(i) 
for i in range (len(l1)): 
print(l2[i],"\t \t \t " , l1[i])

output:
Element 	 	 frequency
13 	 	 	  1
4 	 	 	  2
5 	 	 	  1
3 	 	 	  1
