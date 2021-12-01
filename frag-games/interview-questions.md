# Questions
These questions were asked during frag-games interviews.

##	C++: 
1.	What are the issues with lines 17 and 19?
```
1   int* foo()
2   {
3       int a = 10;
4       return &a;
5    }
6
7
8   class Yolo 
9   {
10  private:
11      static int a = 10;
12  }
13
14  int main()
15  {
16      int *test = foo();
17      cout<< *test;
18
19      cout<<YOLO::a;
20 }
```
2.	Class B inherits from A. How will the stack look like with regards to A and B if you make an object of B?
3.	When can you call static functions in a class?
4.	Lifetime of static variable in a class?
5.	What is scope resolution (or maybe it was access resolution idk)
6.	Why is it better to have static variables in a class instead of global variables?
7.	Write a function to see if two binary trees are mirror of each other
8.	Write another function to mirror a given tree
9.	Make a stack that can be flipped in O(1), ie if it would currently give A B C, it should give C B A after flipping
10.	Identify diamond problem and give solution

##	OOAD:
1.	You have 4 enemy types, they all have some health stamina etc. They also have two attacks, full and half power (so functions). This attack varies from enemy to enemy. Make class diagram

##	Analytical:
1.	There are two rope bridges spanning a river. 4 people need to cross it. The 4 people cross the river in 1, 3, 7, 10 mins. Only one person can be on a bridge at any given time. Minimum time to cross?
