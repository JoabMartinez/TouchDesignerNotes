# TouchDesignerNotes
##These are my notes for Touch Designer (Real Time Engine)

###9/19/18
####https://youtu.be/QpYMClweT6I
#####Python in TouchDesigner |Printing| 

**What is Python?**
It is a high level scripting language that allows us to do different kind of operations with our computer

**Python in TouchDesigner**
How to use the scripting element of Python to let us achieve particular ends.

**Use Text DAT to code**

You can multiply using Python by using a variable or a float and multi/add/subtr/divide it
  
  my_number = 2
  print(my_number * 2)
                       
                       outcome = 4
                       
When you multiply with a Boolean then you are multiplying 1(True) or 0(False)
  
  my_bool = True
  print (my_bool *2)
                      
                      outcome = 2
  my_bool = False
  print (my_bool *2)
                      
                      outcome = 0
                      
 When you want to print something in multiple lines then...
 
 
 /n = new Line
  
  
  ex 1. I can imagine a magical situation n/where I want to print n/out something on multiple lines n/right?
                      
                      
                      outcome = I can imagine a magical situation
                                where I want to print
                                out something on multiple lines
                                right?
                                
  ex 2. Make a Variable called text
        
        
        text = '''I can imagine a magical situation where I want to print out something on multiple lines right?'''
        print (text)
        
                      outcome = I can imagine a magical situation
                                where I want to print
                                out something on multiple lines
                                right?
                                
  ex 3. Define the Lines individually
  
        line1 = "I can imagine a magical situation"
        line2 = "where I want to print"
        line3 = "out something on multiple lines"
        line4 = "right?"
        print (line1)
        print (line2)
        print (line3)
        print (line4)
        
                      outcome = I can imagine a magical situation
                                where I want to print
                                out something on multiple lines
                                right?
                                
       or print it this way
       
       print (line1, line2, line3, line4)
       
                      Same outcome as top
                      
ex 4. lastly, this way

        line1 = "I can imagine a magical situation"
        line2 = "where I want to print"
        line3 = "out something on multiple lines"
        line4 = "right?"
        print (line1)
        print (line2)
        print (line3)
        print (line4)
        new_line = '\n'
        
        print (line1, new_line, line2, new_line, line3, new_line, line4)
        
                     outcome = I can imagine a magical situation
                                where I want to print
                                out something on multiple lines
                                right?
                                
      but when you add it...
      
      print (line1 + new_line + line2 + new_line + line3 + new_line  + line4)
      
                     outcome = I can imagine a magical situation
                               where I want to print
                               out something on multiple lines
                               right?      

**Terms:**
Print - Prints whatever we have inside the quotes
  ex. print ("Hello World")
String - A string is a list of characters that are in order that don't include any numbers.
  ex. print ("This is a string")
Integer - A Whole number                (look at C# notes)
  ex. print ("5")
Float - A number with a decimal         (look at C# notes)
  ex. print ("5.1")
Booleans - True or False Statements. They are evaluated with 1's and 0's.     (look at C# notes)
  ex. print ("True")  or print ("False")
Variables - It is nothing but just reserves memory location to store value    (look at C# notes)
  ex. text= "Hello stranger"     text is the vatiable
Multi-Line string = When you got text that runs over multiple lines
