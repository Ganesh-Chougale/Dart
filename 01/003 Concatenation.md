### 1. `Concatenation`  
```dart
void main(){
    int age = 25;
    String name = "Raju";
    double penPrice = 20.5;
  
  print("Hello, my name is " + name + " & my age is " + age.toString());
}
``` 
#### Output:  
```Terminal
Hello, my name is Raju & my age is 25
```  
### 2. `String Interpolation`
```dart
void main(){
    int age = 25;
    String name = "Raju";
    double penPrice = 20.5;
  
  print("Hello, my name is $name. my age is $age, i have pen worth $penPrice");
}
``` 
#### Output:  
```Terminal
Hello, my name is Raju. my age is 25, i have pen worth 20.5
```  

### 3. `Expression` {}  
```dart
void main(){
  
    int age = 25;
    print("Next year I will be ${age + 1}");
  
    int var1 = 10;
    int var2 = 20;
    print("sum ${var1 + var2}");
  
}
```  
#### Output:  
```Terminal
Next year I will be 26
sum 30
```  