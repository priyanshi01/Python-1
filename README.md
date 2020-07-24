# Python
  This is the file that includes system thinking python codes.
  
  #  Python-code-1:
     function to iteratively sum up the value x**n/n! from n=1 to a given N for a given x , 
     i.e., F(x, n) = 1 + [\sum_{i = 1}^N (x**n/n!)]
    
  # Python-code-2:
    function to iteratively sum up the value x**n/n! from n=1 to a chosen value of N such that 
    F(x, N) - F(x, N-1) < ϵ for a given real number x, and positive small number ϵ.
    
  # Python-code-3:
    Create a list of 10 ordered pairs  (x,y),  x ϵ [−6,6]  such that they satisfy the equation  x2+y2=r2  where  r=6.
    
  # Python-code-4:
    We have a list of tuple representing the name and height (in cms) of 5 students respectively. Convert the list into 
    a dictionary so that we can access the student's height from their names.

    data = [('Sumit', 183), ('Rahul', 175), ('Kritika', 170), ('Harshit', 177), ('Deepak', 162)]
    
  # Python-code-5:
    Write a function which takes list of random integers as an input and returns the list all the unique values present 
    in that list. For ex:

     Input: [1, 2, 4, 4, 3, 2, 1, 1, 2, 4, 5, 3]
     Output : [1, 2, 3, 4, 5]
     
  # Python-code-6:
    Write a program to generate a dictionary that contains the number between  1  and  n  in the form of  (key:value)=(x:x2)  
    where  n=100 . For ex:
    If n = 7 then output will be = {0:0, 1:1, 2:4}
    
  # Python-code-7:
    Write a python function which accpets a tuple representing the fields (func,  xa ) where 'func' is any function  f(x)  and  xa  
    is a point on which you have to find the slope i,e;  df(x)dx  and return a tuple of (slope,  xa ,  f(xa) ,  Δx ) where  Δx→0  but  Δx≠0 .

    Remember :  limΔx→0f(xa+Δx)−f(xa)Δx
    
  # Python-code-8:
    Write a python function which accepts two arguments ( n ,  a ) and returns a tuple of  n  elements where  nth  element should 
    be :  nthelement=1+a1!+a22!+a33!+...+ann!  and  a  should be any positive number. (Observe the last 10 values of returned tuple if  n>20 )
    
  # Python-code-9:
    Write a python function which generates the list of  n  dictionaries representing  n  students. Each dictionary should have two keys Name and Marks, 
    the value of Marks key should be a list of 10 elements representing marks in 10 subjects as  [a1,a2,a3,a4,...,a10] . 
    Create another function which accepts such dictionary and performs operation on marks and returns a list as  [α1,α2,α3,α4,...,α10]  
    where  αi=βαi−1+(1−β)ai  and  β=0.99, α0=1,i=1,2,3,...,10
    
  # Python-code-10:
    Create a dictionary, with keys should be the number from 1 to 100 (1 and 100 both inclusive) and the value should be the list of string 
    representing whether that key is 'Prime', 'Fibonacci' (if that number exist in Fibonacci sequence), 'Square' or all of three. 
    Also write a function which accepts a dictionary (which you will create) and string Prime, Fibonacci or Square and by searching through 
    dictionary it should return a tuple of that numbers.
