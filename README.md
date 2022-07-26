# DART Notes

## 🏆 Track your prgress
- [ ] [⭐ "Hello, World!" program](https://github.com/M0xYasser/DART-Notes#-hello-world-program)
- [ ] [💬 Comments](https://github.com/M0xYasser/DART-Notes#-comments)
- [ ] [ℹ️ Data Types & Variables](https://github.com/M0xYasser/DART-Notes#ℹ%EF%B8%8F-data-types--variables)
- - [ ] [1️⃣ Numbers](https://github.com/M0xYasser/DART-Notes#1%EF%B8%8F⃣-numbers)
- - [ ] 2️⃣ String
- - [ ] 3️⃣ Boolean

<details>
<summary>

### ⭐ "Hello, World!" program

</summary>

Let's start with the first program which is **Hello, World!** program.
```dart
void main() {
  print("Hello, World!");
}
```

</details>
<details>
<summary>

### 💬 Comments

</summary>

**Comments** are very important and are a guide to the code for you and other developers to understand the code.
```dart
void main() {
  // This is the example of single-line comment
  
  /* This is the example of
     multi-line comment */   
}
```

</details>
</details>
<details>
<summary>

### ℹ️ Data Types & Variables

</summary>

The way to initialize variables is :
```
Data_Types Variable_Name = Value ;
```
The way to declare variables is :
```
Data_Types Variable_Name ;
```
> Notes : All data types in dart have the initial value by default `null`
#### 1️⃣ Numbers
The first type is Numbers, and is used to store numeric values.
It is classified into two main types `int` and `double`.
```dart
void main() {
  // `int` that represents a valid number.
  int age = 22;
  // `double` that represents a decimal number.
  double height = 185.5;
}
```
And you can also replace them with `var`.
 
`var` can be initialized as any type.
> Notes : `var` can't change **Type of the variable**, but can change **Value of the variable** later in code.
```dart
void main() {
  var age = 22;
  var height = 185.5;
}
```
#### 2️⃣ String
A string is the sequence of the character, and is used to store the data like **name, address, special character, etc**.
```dart
void main() {
  String name_1 = "M0xYasser" ;
  // OR can us var
  var name_2 = "M0xYasser" ;
}
```
> Notes : The letter **S** in the word `String` is a **Capital letter**.
#### 3️⃣ Boolean
The Boolean type represents the two values **true and false**. 
```dart
void main() {
  bool flag_1 = true ;
  var flag_2 = false ;
}
```

</details>
