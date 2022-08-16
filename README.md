from datetime import date

class Employee:
   def__init__(self,name,rollno,dob,city):
      self.name=name
      self.dob=dob
      self.eno=eno
      self.city=city

   def address(self):
      addr=f"Name : {self.name}\nDOB : {self.dob}\nEno : {self.eno}\nCity : {self.city}"
      return addr

   def joining(self):
      current_year = date.today().year
      return current_year = self.dob
      
 emy1 = Employee('nandini',001,2020,"Chennai")
 emy2 = Employee('deepa',002,2021,"Trichy")

Employee.joinig(emy1)
print(emy1.joinig())

