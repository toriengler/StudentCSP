.. qnum::
   :prefix: 7-8-
   :start: 1

Mixed Up Code Practice
------------------------------

Try to solve each of the following. Click the *Check Me* button to check each solution.  You will be told if your solution is too short, has a block in the wrong order, or you are using the wrong block.  Some of the problems have an extra block that isn't needed in the correct solution.  Try to solve these on your phone or other mobile device!

.. parsonsprob:: ch7ex1muc
   :numbered: left
   :practice: T
   :adaptive:

   The following program segment should print out each number in the list <i>fruits</i> on separate lines.</p>
   -----
   fruits=["apple", "orange", "banana", "cherries"]
   =====
   new_string='' #distractor
   =====
   for fruit in fruits:
   =====
    print(fruit)
   =====
   print(x) #distractor
   =====
   print("The ") #distractor

.. parsonsprob:: ch7ex2muc
   :numbered: left
   :practice: T
   :adaptive:

   Define a function that takes a number and multiplies that number by 2.</p>
   -----
   def sum(): #distractor
   =====
   count=0 #distractor
   =====
   def mult(num):
   =====
    new_num=num * 2
   =====
    print(num) #distractor
   =====
    return new_num

.. parsonsprob:: ch7ex3muc
   :numbered: left
   :practice: T
   :adaptive:

   Add the numer 5 to the current sum 12 times then print the final sum.</p>
   -----
   sum=0
   =====
   for x in range(1,6):
   =====
   print(x) #distractor
   =====
    sum=sum+5
   =====
    print('60') #distractor
   =====
   print(sum) 

.. parsonsprob:: ch7ex4muc
   :numbered: left
   :practice: T
   :adaptive:

   Using the accumulator pattern, count how many animals are in the list <i>animals</i>.</p>
   -----
   animals=["lion", "tigers", "bears", "bird", "dogs", "cats","snakes"]
   =====
   accum=0
   =====
   for animal in animals:
   =====
    accum+=1
   =====
   print(animal) #distractor
   =====
   print(accum) 
   =====
   accum+=animal #distractor
   