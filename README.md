# Python Object Oriented Programming


What is Oops:

 * Oops was invented in 1960
 * Oops is a paradigm(pattern) for code organization and design
 * promotes collaboration, code extension and maintenance

The Oops paradigm:
 * Organizes data into objects and functions into methods
 * Defines object specifications ( data and methods ) in classes

Procedural paradigm vs Object Paradigm:
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
