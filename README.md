## Determine-which-class-a-given-Bus-object-belongs-to-Check-type-of-an-object-
## Sample code to check the details 
```sh
class Vehicle:
    def __init__(self, name, mileage, capacity):
        self.name = name
        self.mileage = mileage
        self.capacity = capacity

class Bus(Vehicle):
    pass

School_bus = Bus("School Volvo", 12, 50)

# use Python's built-in type() function
print(type(School_bus))
```
## Expected Output
<class '__main__.Bus'>
