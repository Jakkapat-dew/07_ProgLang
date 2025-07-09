Basic Python
==

## Parameter definition ##
- Using Python naming conventions (from PEP8 - Key style guide)
#### ***snake_case*** for parameters name ####
```py
str first_name = ""
int age = 10
list days = ["Mon", "Tue", "Wed"]
```

#### ***UPPER_CASE*** for constant ####
```py
PI = 3.14
DATABASE_NAME = "my_application_db"
```

#### ***snake_case*** for method/function name ####
```py
def calculate_room_area(width: float, height: float) -> float{
    area =  width * height
    return area
}
```

#### ***PascalCase*** for class name in PythonOOP ####
```py
class RoomService:
    # __dundle__ for magic method (this is constructor)
    self.__init__(self):            
        self.name = "Sweet"
        self.width = 10
        self.height = 10
        # _single_leading_underscore for protected, private field/method
        self._position = ''
        # __double_leading_underscore for strongly private field/method
        self.__price = 3000 
        pass
```

#### ***lowercase*** for package name #### 
```py
import pandas;
import numpy;
```

## Comments ##
```py
# For shortly explained
int a = 1;      # inline comment (enable code)
# int b = 1;    # inline comment (disable code )

"""
# multiple line comment using 
float a = 1; 
float b = 1;
"""
# For doc string
def add_integer(x: int, y: int) -> int:
    """Function to add two integers.
    Arguments:           
        x (int): First integer.
        y (int): Second integer.
    Returns:
        int: Sum of x and y.
    """
    return int(x + y)

sum = add_integer(x=1, y=2)
print(sum)
```

## Data type casting ##
```py
str a = "10.11"
int b = int(a)
float c = float(a)
print(a, b)
print(f"type a: {type(a)}, type b: {type(b)}, type c: {type(c)}")
```

## Operators ##
### Arithmetic operators for mathematical operation ###
| Name            | Operator  | Example   | 
| :-------------- | :---:     | :---:     |
| Addition        |   +       | x + y     |
| Subtraction     |   -       | x - y     |
| Multiplication  |   *       | x * y     |
| Division        |   /       | x / y     |
| Modulus         |   %       | x % y     |
| Exponentiation  |   **      | x ** y    |
| Floor division  |   //      | x // y    |

```py
# Example
x = 10
y = 2
print(f"x + y": {x + y})
print(f"x - y": {x - y})
print(f"x * y": {x * y})
print(f"x / y": {x / y})
print(f"x % y": {x % y})
print(f"x ** y": {x ** y})
print(f"x // y": {x // y})
```

### Assignment Operators ###
| Operator  | Example   | Same As    |
| :------:  | :---:     | :---:      |
| ++        | x ++      | x = x + 1  |
| +=        | x += 5    | x = x + 5  |
| --        | x --      | x = x - 1  |
| -=        | x -= 5    | x = x - 5  |
| *=        | x *= 5    | x = x * 5  |
| /=        | x /= 5    | x = x / 5  |
| %=        | x %= 5    | x = x % 5  |
| **=       | x **= 5   | x = x ** 5 |

#### bit operator ####
| Operator  | Example   | Same As    |  Description |
| :------:  | :---:     | :---:      | :---: |
| &=        | x &= 5    | x = x & 5  | AND
| \|=       | x \|= 5   | x = x \| 5 | OR
| ^=        | x ^= 5    | x = x ^ 5  | XOR
| >>=       | x >>= 5   | x = x >> 5 | Shift bit right
| <<=       | x <<= 5   | x = x << 5 | Shift bit left

```py
# Example
x = 1
x += 3
print(x) # 4
```

### Comparison Operators ###
| Name                      | Operator  | Example   | 
| :--------------           | :---:     | :---:     |
| Equal                     |   ==      | x == y    |
| Not equal                 |   !=      | x != y    |
| Greater than              |   >       | x > y     |
| Less than                 |   <       | x < y     |
| Greater than or equal to  |   >=      | x >= y    |
| Less than or equal to     |   <=      | x <=> y   |


## String Object ##
```py
text = "Joey Wang"
name1 = text[0:7]           # Slice
print(name1)

name2 = text.split(" ")[0]  # Split with a space
print(name2)

print(name2.upper())        # Modify to UPPER
print(name2.lower())        # Modify to lower

a = "Joey"
b = "Wang"
c = a + "" + b
print(c)                    # Concatenation

# string format
name = "Joey"
age = 18
txt_intro = f"My name is {name}, I am {age}"
print(txt_intro)
```

