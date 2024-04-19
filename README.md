# 1st code: Composition > inheritance​ 
# instructions
Hello! welcome to the my project 

#parent class
class parent :
     # constructor
     #variable of parent class


     #methods

     ....


     #Child class inheriting parent class
class child(parent)
 
        #constructor od child class
        #variable of child class
        #methods of child class

# example of composition > inheritance code

   this is my own code
  parent class 

class Parent: 

   # parent class method 

    def a1(self): 
           print('Parent Class Method called...') 

   #child class inheriting parent class 
class Child(Parent): 

    # child class constructor 
    def __init__(self): 
        print('Child Class object created...') 

            #child class method 
    def a2(self): 
            print('Child Class Method called...') 

   
#creating object of child class 
obj = Child() 

   #calling parent class a1() method 
   obj.m1() 

   #calling child class a2() method 
    obj.m2() 
  


 # 2nd code: open/closed principle
 # instructions

 welcome! this is my another code
 The circle and sequre classes are closed for modification
 
 if we want to add new shapes, we can simply create a new class

 we do not have to modify the existing circle or rectangle classes

# example of open/closed principle
 class Shape: 
        def draw(self): 
            raise NotImplementedError() 
     
    class Circle(Shape): 
        def draw(self): 
            print('Drawing Circle') 
     
    class rectangle(Shape): 
        def draw(self): 
            print('Drawing rectangle') 
     
    if __name__ == '__main__': 
        shapes = [Circle(), rectangle()] 
        for shape in shapes: 
            shape.draw() 


# 3rd code SOLID principle 

3rd Code: SOLID Principle
Hello! This is the third and longest of the three codes I'll talk about. Given that it covers all five concepts and combines them into one, it is fairly long. I'm talking about the "SOLID" principle. I'll reveal where each of these five concepts may be located in this final code and explain how it works.

Single Responsibility Principle:
According to this method, it's crucial that each class only have one duty or job. Each class is distinct and focuses on a single topic, as you can see. First off, we have a class called "Support Ticket" that aids in ticket creation. The second class under "HelpDeskSystem" will concentrate on the many features of your ticketing system. The last class will then be designated as your main by the user, allowing the code to run and display the tickets the user has produced.

Open/Closed Principle:
If your code is open for extensions but closed for alteration, this principle examines that. To add new functionality without changing the existing code, you should write code that can be extended. We once more make reference to the classes we previously discussed. The "SupportTicket" class from the first class, which we indicated was used to produce tickets, is now used to amend those tickets using the "HelpDeskSystem" class from the second class.

Liskov Substitution Principle
This principle is for code such as subtypes to be substitued in place of their parent types without causing any issues. Like for instance, when submitting tickets this method creates a new Ticket within the first class with the given parameters and subs it to the tickets list.

Interface Segregation Principle
Having the fewest possible methods in a class is the whole point of the interface segregation principle. This results in definitions that are more concentrated and frequently divide a design into multiple classes to isolate the impact of any changes. The user will then need a new class that focuses on the various ticketing system features, for instance, and everything will run via that primary class. Add "class HelpDeskSystem" after that. You may depict the full helpdesk system with the aid of this class. This lesson will teach you how to generate tickets, display them, reopen them, reply to them, and show their statistics.

Dependency Inverion Principle
This is last and final principle and its main purpose is to focus on the abstractions of your code and how it should not depend upon the details. Instead the details should depend upon the abstractions. 

Conclusion
With the use of these principles it will help ensure that your code is maintainable, extensible, and testable. Using this has benefitted me on understanding each principle and how to create codes. Thank you very much for viewing my readme!

  
