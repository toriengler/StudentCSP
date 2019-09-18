.. qnum::
   :prefix: 9-7-
   :start: 1

Mixed Up Code Practice
------------------------------

Try to solve each of the following. Click the *Check Me* button to check each solution.  You will be told if your solution is too short, has a block in the wrong order, or you are using the wrong block.  Some of the problems have an extra block that isn't needed in the correct solution.  Try to solve these on your phone or other mobile device!

.. parsonsprob:: ch9ex1muc
   :numbered: left
   :practice: T
   :adaptive:

   The following program segment should print out a sentence that combines strings to form the following sentence: "The brown dog jumped over the fence". The blocks have been mixed up. Drag the blocks from the left and put them in the correct order on the right.  Click the <i>Check Me</i> button to check your solution.</p>
   -----
   fido="brown dog"
   =====
   action=" jumped over the fence"
   combine_string=combine_string + action
   =====
   combine_string="The "
   =====
   combine_string=combine_string + fido
   =====
   print(combine_string)
   =====
   print(combine_string + "The ") #distractor
        

.. parsonsprob:: ch9ex2muc
   :numbered: left
   :practice: T
   :adaptive:

   Combine the strings to wish your friend a happy birthday! The resulting string should combine the strings "Happy Birthday" and " my friend!" Drag the blocks from the left and put them in the correct order on the right.  Click the <i>Check Me</i> button to check your solution.</p>
   -----
   string1="Happy Birthday" 
   =====
   friend= " my friend!"
   =====
   birthday=" "
   =====
   for char in string1:
      birthday=birthday + char
   =====
   print(birthday + friend)


.. parsonsprob:: ch9ex3muc
   :numbered: left
   :practice: T
   :adaptive:

   Use slicing to join together and print the first and last characters of the given string. Drag the blocks from the left and put them in the correct order on the right. Click the <i>Check Me</i> button to check your solution.</p>
   -----
   to_slice="My favorite food is pizza. Pizza is so good!"
   =====
   new_str=" "
   =====
   new_str=new_str+ to_slice[0] + to_slice[-1]
   =====
   new_str=new_str+ to_slice[1] + to_slice[-1] #distractor
   =====
   print(new_str)


.. parsonsprob:: ch9ex4muc
   :numbered: left
   :practice: T
   :adaptive:

   Print the index associated with the beginning of the word "love" in the string <i>sandwiches</i>. Drag the blocks from the left and put them in the correct order on the right. Click the <i>Check Me</i> button to check your solution.</p>
   -----
   sandwiches="I love peanut butter and jelly sandwiches."
   =====
   index_=sandwiches.find("love")
   =====
   print(index_)
   =====
   print("love") #distractor
   