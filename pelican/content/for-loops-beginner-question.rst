for loops - beginner question
#############################
:date: 2017-02-19 16:52
:slug: for-loops-beginner-question
:status: published

| Greetings!
| I have recently started Python as my first computer language and there
  is one part of the for loops I am having trouble with.
| The objective of the code below is to turn a list [1,1,2,3,3,3,4,4,5]
  into a list with only the unique elements of the first list.
  [1,2,3,4,5] without the use of sets.
| *code:*
| def unique\_list(g): 
|       x = [ ]
|       **for** a **in** g: 
|           ** if** a **not in** x:
|                x.append(a)
| return x
|  
| I understand what each individual part of the code does but the part
  of "**for** a \ **in** g" is what confuses me. I know "g" is the list
  in reference but what is "a"? If it is the elements in "g" how can
  Python tell the difference of each element, if I had numbers and
  strings and symbols?
|  
| Also, the below section is confusing in the sense of what the role of
  "a" is and how does it know which to append? I get that if an "a"
  similar to another "a" is in the list it will not duplicate it but how
  does it know which "a" to append?
| *code:*
| **if** a **not in** x:
|                x.append(a)
|  
| My apologies for the long post and I hope what I asked is
  understandable. Any help would be greatly appreciated!
|  
| All the best,
|  
| Nico
