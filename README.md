# Assignment_1
Q1. 
Sort the list and find the min and max age
      ages=[19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
      ages.sort()
      print(ages)
      b=min(ages)
      c=max(ages)
      print(b)
      print(c)
Add the min age and the max age again to the list
      ages.append(max(ages))
      ages.append(min(ages))
      print(ages)
Find the median age (one middle item or two middle items divided by two)
      
Find the average age (sum of all items divided by their number)
      average = sum(ages) / len(ages)
      print(average)      
Find the range of the ages (max minus min)
     mami= max(ages)-min(ages)
     print(mami) 
Q3.
Create a tuple containing names of your sisters and your brothers (imaginary siblings are 
fine)
     my_tuplebrother =()
     my_tuplebrother= ("minaz", "rajesh", "Srikanth")
     print(my_tuplebrother)
     my_tuplesister =()
     my_tuplesister=(" jineesha", "revathi", "veena")
     print(my_tuplesister)
Join brothers and sisters tuples and assign it to siblings
     my_tuplesiblings = ()
     my_tuplesiblings =  my_tuplebrother + my_tuplesister
     print(my_tuplesiblings)
How many siblings do you have?
     print(len(my_tuplesiblings))
Modify the siblings tuple and add the name of your father and mother and assign it to 
family_members
     my_familymember = ()
     my_familymember = my_tuplesiblings + ("kavitha", "gopal")
     print(my_familymember)
Q6.
“I am a teacher and I love to inspire and teach people”
• How many unique words have been used in the sentence? Use the split methods and set 
to get the unique words.
      text = "I am a teacher and I love to inspire and teach people"
      p = text.split()
      print(p)
      q=p
      z= len(p)
      se =set(q)
      print(z)
      print(se)
Q7.
print("Name \t" "age  " "country " "  city\n" "Asabeneh " "250 " "Finland\t" "helsiniki")
Q8.
      var = int(input())
      Area = 3.14 * var ** 2
      txt = "the area of circle with radius {radius} is {area} meters square".format(radius=var ,area= Area)
      print(txt)
     
     
     
