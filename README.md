class body:
    def b_type(self):
        print("leg", "head", "eye")
body.b_type(1)
hair=body
print(type(hair))


class myclass:
    x=5
p1=myclass
print(p1.x)

class person:
    def __init__(self, name, age):
        self.name=name
        self.age=age
p1=person("john", 35)
p2=person('joshua', 27)
print(p1.name)
print(p1.age)
print(p2.age)

class student:
    def __init__(self, name, age):
        self.name=name
        self.age=age
    def __str__(self):
        return f"{self.name}({self.age})"
h1=student("Hauwa", 25)
print(h1)



class Person:
    """the self parameter those matter you can insert anything you wish, so it can be anything else like any nonsense you wish but it have to be inserted on the first function class bracket """
  def __init__(bighead, name, age):
    bighead.name =name
    bighead.age =age
  def __str__(nonsense):
    return f"{nonsense.name}({nonsense.age})"

p1 = Person("John", 36)

print(p1)

class greetings:
    def __init__(self, name, age):
        self.name=name
        self.age=age
    def my_function(self):
        print('hello welcome ' + self.name)
p3=greetings("musa", 22)
p3.my_function()
