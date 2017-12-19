# Python Object Oriented Programming


### What is Oops:

 * Oops was invented in 1960
 * Oops is a paradigm(pattern) for code organization and design
 * promotes collaboration, code extension and maintenance

### The Oops paradigm:
 * Organizes data into objects and functions into methods
 * Defines object specifications ( data and methods ) in classes

### Procedural paradigm vs Object Paradigm:
* Procedural paradigm

      def increment(val):
          return val+1

      this = 0
      this = increment(this)
      this = increment(this)
      print(this)

* Object Paradigm:

      class MyCustomInc(object):
          def __init__(self):
              self.val = 0
          def increment(self):
              self.val = self.val + 1
          def __repr__(self):
              return str(self.val)

      this = 0
      this = MyCustomInc()
      this.increment()
      print(this)

### Three pillers of Oops:

* Encapsulation
* Inheritance
* Polymorphism


### Modules Vs Classes

* Module is a file that containes python code
* Class  is a Python Code


#### Example:

      from collections import Counter

      #Here 
      #collections is a Module (Python file)
      #Counter is Class (Python Code)


### Some Definations:
* Class     --> Class is a blueprint for an Instance
* Instance  --> Instance is a constructed objcet of class
* Attribute --> Attribute is object value: object.attribute
* Method    --> Method is a callable attribute defined in the class
