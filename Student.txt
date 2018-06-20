class Student:
    def __init__(self,name,rollno):
        self.name=name
        self.rollno=rollno
    def display(self):
        print('Name: {}, RollNo: {}'. \
              format(self.name, self.rollno))
s1= Student('ashu',3)
s2=Student('saurabh',5)

s1.display()
s2.display()