### **변수와 데이터 타입**

파이썬에서는 변수를 선언할 때 특별한 키워드 없이 바로 할당할 수 있습니다. 데이터 타입은 자동으로 인식됩니다.

```jsx
x = 10          # int
y = 20.5        # float
name = "Alice"  # str
is_student = True  # bool
```

### **리스트, 튜플, 딕셔너리**

- **리스트(List)**: 변경 가능(mutable)한 데이터 컬렉션입니다.
- **튜플(Tuple)**: 변경 불가능(immutable)한 데이터 컬렉션입니다.
- **딕셔너리(Dictionary)**: 키-값 쌍으로 이루어진 데이터 컬렉션입니다.

```jsx
# 리스트
fruits = ["apple", "banana", "cherry"]
print(fruits[0])  # apple

# 튜플
coordinates = (10, 20)
print(coordinates[1])  # 20

# 딕셔너리
person = {"name": "John", "age": 30}
print(person["name"])  # John

```

### **제어 구조**

- **조건문(If-Else)**: 조건에 따라 코드의 실행 경로를 결정합니다.
- **반복문(For, While)**: 코드 블록을 여러 번 실행합니다.

```jsx
# If-Else 조건문
age = 20
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")

# For 반복문
for fruit in fruits:
    print(fruit)

# While 반복문
i = 0
while i < len(fruits):
    print(fruits[i])
    i += 1

```

### **함수**

파이썬에서 함수는 **`def`** 키워드를 사용하여 정의합니다. 함수는 코드의 재 사용성을 높여 줍니다.

```jsx
def greet(name):
    print("Hello, " + name + "!")

greet("Alice")

```

### **예제: 간단한 계산기**

두 숫자를 입력 받아 덧셈, 뺄셈, 곱셈, 나눗셈을 수행하는 간단한 계산기를 만듭니다.

```jsx
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error! Division by zero."
    else:
        return x / y

# 사용 예
print(add(10, 5))       # 15
print(subtract(10, 5))  # 5
print(multiply(10, 5))  # 50
print(divide(10, 5))    # 2.0

```

#
