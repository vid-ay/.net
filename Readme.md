<a id="top"></a>

# Practical Question Bank — C#, ASP.NET and PWA

Complete solutions for the **43-question practical bank**: question → source code → sample output, with step-by-step instructions to run each program in **Visual Studio**.

---

## 📑 Index

### 🔹 Part 1 — How to Run (Visual Studio)

| Run type | Programs | Steps |
|---|---|---|
| Prerequisites & workloads | – | [Go](#how-to-run) |
| Console App (C#) | Q1 – Q19 | [Go](#run-console) |
| ASP.NET Core MVC | Q20 – Q22 | [Go](#run-mvc) |
| ASP.NET Web Forms (.NET Framework) | Q23 – Q30 | [Go](#run-webforms) |
| ASP.NET Core minimal API (Auth / Web API) | Q31 – Q33 | [Go](#run-core) |
| Progressive Web Apps | Q34 – Q43 | [Go](#run-pwa) |
| Troubleshooting | – | [Go](#troubleshooting) |

### 🔹 Part 2 — Questions and Code

| Section | Questions | Jump to |
|---|---|---|
| A. C# Programming and Object-Oriented Concepts | Q1 – Q19 | [Go](#section-a) |
| B. ASP.NET Web Forms, MVC and Core | Q20 – Q33 | [Go](#section-b) |
| C. Progressive Web Applications (PWA) | Q34 – Q43 | [Go](#section-c) |

#### A. C# Programming and Object-Oriented Concepts

| Q# | Question | Run type | Code |
|---|---|---|---|
| 1 | Write a C# program to create methods for addition, subtraction, multiplication, and division. Use delegates to invoke these methods with suitable parameters. | [Console App](#run-console) | [View code](#p1) |
| 2 | Write a C# program to demonstrate a multicast delegate that invokes multiple methods. | [Console App](#run-console) | [View code](#p2) |
| 3 | Write a C# program to demonstrate delegates and events. Also demonstrate an event with a suitable example. | [Console App](#run-console) | [View code](#p3) |
| 4 | Write a C# program to demonstrate function/method overloading by creating multiple methods with the same name but different parameters. | [Console App](#run-console) | [View code](#p4) |
| 5 | Write a C# program to demonstrate constructor overloading by defining multiple constructors with different parameter lists in the same class. | [Console App](#run-console) | [View code](#p5) |
| 6 | Write a C# program to demonstrate Single Inheritance using a base class and a derived class. | [Console App](#run-console) | [View code](#p6) |
| 7 | Write a C# program to demonstrate Multilevel Inheritance using suitable classes and objects. | [Console App](#run-console) | [View code](#p7) |
| 8 | Write a C# program to demonstrate any two types of inheritance. | [Console App](#run-console) | [View code](#p8) |
| 9 | Write a C# program to demonstrate the different types of inheritance: Single, Multilevel, and Hierarchical. | [Console App](#run-console) | [View code](#p9) |
| 10 | Write a C# program to demonstrate multiple inheritance using interfaces. Define `IPrint` and `IShow` and implement them in a single class named `Demo`. | [Console App](#run-console) | [View code](#p10) |
| 11 | Write a C# program to demonstrate the use of interfaces by defining contracts that classes must implement. | [Console App](#run-console) | [View code](#p11) |
| 12 | Create an interface `IShape` containing a method `CalculateArea()`. Implement the interface in `Circle` and `Rectangle` classes and display their respective areas. | [Console App](#run-console) | [View code](#p12) |
| 13 | Create a `BankAccount` class with `AccountNumber` and `Balance` properties. Implement validation to ensure that the balance cannot be negative. | [Console App](#run-console) | [View code](#p13) |
| 14 | Write a C# program to demonstrate exception handling using try-catch-finally blocks. Handle the exception that occurs when a number is divided by zero. | [Console App](#run-console) | [View code](#p14) |
| 15 | Write a C# program to demonstrate exception handling using try-catch-finally blocks, custom exceptions, and multiple catch handlers. | [Console App](#run-console) | [View code](#p15) |
| 16 | Write a C# program to accept the number of rows from the user and display Pascal's triangle using nested loops. | [Console App](#run-console) | [View code](#p16) |
| 17 | Write a C# program to print Floyd's triangle up to N rows, where N is input by the user. | [Console App](#run-console) | [View code](#p17) |
| 18 | Write C# code to accept the names of 10 cities from the user and arrange the city names in sorted order. | [Console App](#run-console) | [View code](#p18) |
| 19 | Create a C# application to perform basic arithmetic operations. | [Console App](#run-console) | [View code](#p19) |

#### B. ASP.NET Web Forms, MVC and Core

| Q# | Question | Run type | Code |
|---|---|---|---|
| 20 | Develop an ASP.NET MVC application that accepts two numbers from the user, performs addition, subtraction, multiplication, and division, and displays the results on the webpage. | [ASP.NET Core MVC](#run-mvc) | [View code](#p20) |
| 21 | Develop an ASP.NET MVC application that accepts a number from the user and finds its square and cube. Display the results on the webpage. | [ASP.NET Core MVC](#run-mvc) | [View code](#p21) |
| 22 | Create an MVC application to perform basic arithmetic operations. | [ASP.NET Core MVC](#run-mvc) | [View code](#p22) |
| 23 | Create an ASP.NET Web Forms Student Registration Form using Label, TextBox, RadioButton, DropDownList, CheckBox, Calendar, and Button controls. Display the submitted details using a Label control. | [ASP.NET Web Forms](#run-webforms) | [View code](#p23) |
| 24 | Create an ASP.NET Web Forms Employee Registration Form using Label, TextBox, RadioButton, DropDownList, CheckBox, Calendar, and Button controls. Display the submitted details using a Label control. | [ASP.NET Web Forms](#run-webforms) | [View code](#p24) |
| 25 | Write an ASP.NET Web Forms program to design a Student Feedback Form using TextBox, RadioButton, CheckBox, DropDownList, and Button controls. | [ASP.NET Web Forms](#run-webforms) | [View code](#p25) |
| 26 | Create an ASP.NET Web Forms Registration Form using RequiredFieldValidator, RangeValidator, RegularExpressionValidator, and CompareValidator controls. | [ASP.NET Web Forms](#run-webforms) | [View code](#p26) |
| 27 | Write an ASP.NET Web Forms program to validate student registration details and display the submitted information using appropriate controls. | [ASP.NET Web Forms](#run-webforms) | [View code](#p27) |
| 28 | Create an ASP.NET Web Forms application that displays rotating advertisements using the AdRotator control and an advertisement XML file. | [ASP.NET Web Forms](#run-webforms) | [View code](#p28) |
| 29 | Develop a web application to demonstrate session cookies and persistent cookies. Store and retrieve user information using cookies. | [ASP.NET Web Forms](#run-webforms) | [View code](#p29) |
| 30 | Create a web application to demonstrate the use of different types of cookies. | [ASP.NET Web Forms](#run-webforms) | [View code](#p30) |
| 31 | Develop an ASP.NET Core web application to authenticate users and restrict access to pages based on user roles, such as Admin and User. | [ASP.NET Core (minimal API)](#run-core) | [View code](#p31) |
| 32 | Create an ASP.NET Core application to demonstrate Authentication and Authorization. | [ASP.NET Core (minimal API)](#run-core) | [View code](#p32) |
| 33 | Create a simple ASP.NET Core Web API that returns student details, such as Roll Number, Name, Course, and Marks, in JSON format. Test the endpoint using a browser or Postman. | [ASP.NET Core (minimal API)](#run-core) | [View code](#p33) |

#### C. Progressive Web Applications (PWA)

| Q# | Question | Run type | Code |
|---|---|---|---|
| 34 | Develop a simple college website containing information about courses, faculty, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker. | [PWA (static files)](#run-pwa) | [View code](#p34) |
| 35 | Develop a simple company website containing information about products, services, About Us, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker. | [PWA (static files)](#run-pwa) | [View code](#p35) |
| 36 | Develop a simple hotel website containing information about rooms, food, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker. | [PWA (static files)](#run-pwa) | [View code](#p36) |
| 37 | Develop a College Information Portal website and convert it into a Progressive Web Application (PWA) by implementing a Service Worker and Web App Manifest. | [PWA (static files)](#run-pwa) | [View code](#p37) |
| 38 | Create a PWA that displays a custom offline page whenever the user loses internet connectivity. Use a Service Worker to cache the required resources. | [PWA (static files)](#run-pwa) | [View code](#p38) |
| 39 | Develop a PWA that supports offline functionality using a Service Worker and the cache-first caching strategy. | [PWA (static files)](#run-pwa) | [View code](#p39) |
| 40 | Develop a PWA that caches HTML, CSS, JavaScript, and image files using a Service Worker so that the application can work without an internet connection. | [PWA (static files)](#run-pwa) | [View code](#p40) |
| 41 | Create an HTML page as the starting point of a PWA and link it to a `manifest.json` file for application configuration. | [PWA (static files)](#run-pwa) | [View code](#p41) |
| 42 | Create a `manifest.json` file and configure the application name, icons, start URL, theme color, background color, and display mode. | [PWA (static files)](#run-pwa) | [View code](#p42) |
| 43 | Create a PWA with a Web App Manifest file containing the app name, icons, start URL, and display mode. Implement push notifications in the PWA. | [PWA (static files)](#run-pwa) | [View code](#p43) |

[⬆ Back to top](#top)

---

<a id="how-to-run"></a>

## 🚀 How to Run (Visual Studio)

Install **Visual Studio 2022 (or later)** — the purple icon — with these workloads (Visual Studio Installer → *Modify*):

- **.NET desktop development** (console apps)
- **ASP.NET and web development** (MVC, Web Forms, Web API, PWA)

Then follow the steps for the type of program you want to run.

<a id="run-console"></a>

### 1️⃣ Console programs (Q1 – Q19)

1. Open Visual Studio → **Create a new project**.
2. Choose **Console App** (C#, .NET) → **Next**.
3. Name it (e.g. `Program01`) → **Next** → **Create**.
4. Open `Program.cs`, **delete everything**, and paste the program code.
5. Press **Ctrl + F5** (Run without debugging). The console window shows the output.
6. Programs that read input (Q15 – Q19) wait for you to type in the console window.

<a id="run-mvc"></a>

### 2️⃣ ASP.NET Core MVC (Q20 – Q22)

1. **Create a new project** → **ASP.NET Core Web App (Model-View-Controller)** → **Next**.
2. Name it `Demo` (the code uses the namespace `Demo`) → **Create** (pick the latest .NET, *Authentication: None*).
3. In **Solution Explorer**, right-click `Models` / `Controllers` / `Views` → **Add → Class / Controller / View** and paste each file as shown.
   - For views: create folder `Views/Calc` (or `Number`, `Calculator`) and add `Index.cshtml`.
4. Make sure `Program.cs` contains the default MVC routing:
   ```csharp
   builder.Services.AddControllersWithViews();
   app.MapControllerRoute(name: "default", pattern: "{controller=Home}/{action=Index}/{id?}");
   ```
5. Press **F5** and browse to `/Calc`, `/Number` or `/Calculator`.

<a id="run-webforms"></a>

### 3️⃣ ASP.NET Web Forms (Q23 – Q30)

> Web Forms works only on **.NET Framework** (not .NET Core).

1. **Create a new project** → **ASP.NET Web Application (.NET Framework)** → **Next** → name it → **Create**.
2. Select the **Web Forms** template → **Create**.
3. Right-click the project → **Add → Web Form** → give the page name (e.g. `Student`).
4. In the `.aspx` file keep the `<%@ Page ... %>` line that Visual Studio generated (it uses `CodeBehind`) and replace only the `<form>…</form>` part with the code shown.
5. Open the `.aspx.cs` file (expand the page in Solution Explorer) and paste the code-behind. Keep the class name equal to the page name.
6. Right-click the `.aspx` page → **Set as Start Page** → press **F5**.
7. For Q28 also add the `Ads.xml` file and an `Images` folder with `ad1.png`, `ad2.png`.

<a id="run-core"></a>

### 4️⃣ ASP.NET Core minimal API (Q31 – Q33)

1. **Create a new project** → **ASP.NET Core Empty** → **Next** → name it → **Create**.
2. Open `Program.cs`, replace everything with the program code.
3. Press **F5**. Test endpoints in the browser, or with **Postman** (Q31, Q33).
4. Each Program.cs example is a **separate project**.

<a id="run-pwa"></a>

### 5️⃣ Progressive Web Apps (Q34 – Q43)

1. **Create a new project** → **ASP.NET Core Empty** (this is just used as a local web server).
2. Replace `Program.cs` with:
   ```csharp
   var builder = WebApplication.CreateBuilder(args);
   var app = builder.Build();
   app.UseDefaultFiles();
   app.UseStaticFiles();
   app.Run();
   ```
3. Right-click the project → **Add → New Folder** → `wwwroot` (if it doesn't exist).
4. Add all PWA files (`index.html`, `manifest.json`, `sw.js`, icons …) **inside `wwwroot`**.
5. Press **F5** → the browser opens on `https://localhost:xxxx` (localhost is allowed for service workers).
6. Test the PWA in **Chrome / Edge**: press **F12 → Application** tab
   - **Manifest** → check name, icons, install button
   - **Service Workers** → check it is *activated and running*, tick **Offline**, then reload to test offline mode.
7. Click the **install icon** in the address bar to install the app.

**Icons:** every PWA needs `icon-192.png` (192×192) and `icon-512.png` (512×512). Create any simple square PNGs and place them next to `manifest.json`.

[⬆ Back to top](#top)

---

<a id="section-a"></a>

# A. C# Programming and Object-Oriented Concepts

*Run type: Console App — see [Console programs](#how-to-run).*

---

<a id="p1"></a>

## Program 1 — Delegates for arithmetic operations

**Question:** Write a C# program to create methods for addition, subtraction, multiplication, and division. Use delegates to invoke these methods with suitable parameters.

```csharp
using System;
class Program {
    delegate double Operation(double a, double b);
    static double Add(double a, double b) => a + b;
    static double Sub(double a, double b) => a - b;
    static double Mul(double a, double b) => a * b;
    static double Div(double a, double b) => a / b;
    static void Main() {
        Operation op = Add;
        Console.WriteLine("Addition: " + op(20, 10));
        op = Sub; Console.WriteLine("Subtraction: " + op(20, 10));
        op = Mul; Console.WriteLine("Multiplication: " + op(20, 10));
        op = Div; Console.WriteLine("Division: " + op(20, 10));
    }
}
```

**Output**
```
Addition: 30
Subtraction: 10
Multiplication: 200
Division: 2
```

[⬆ Back to top](#top)

---

<a id="p2"></a>

## Program 2 — Multicast delegate

**Question:** Write a C# program to demonstrate a multicast delegate that invokes multiple methods.

```csharp
using System;
class Program {
    delegate void MyDelegate();
    static void Method1() { Console.WriteLine("Method 1 called"); }
    static void Method2() { Console.WriteLine("Method 2 called"); }
    static void Method3() { Console.WriteLine("Method 3 called"); }
    static void Main() {
        MyDelegate del = Method1;
        del += Method2;
        del += Method3;
        del();
    }
}
```

**Output**
```
Method 1 called
Method 2 called
Method 3 called
```

[⬆ Back to top](#top)

---

<a id="p3"></a>

## Program 3 — Delegates and events

**Question:** Write a C# program to demonstrate delegates and events. Also demonstrate an event with a suitable example.

```csharp
using System;
class Notification {
    public delegate void Notify();
    public event Notify OnNotify;
    public void SendMessage() {
        Console.WriteLine("Sending message...");
        OnNotify?.Invoke();
    }
}
class Program {
    static void ShowMessage() { Console.WriteLine("Event triggered!"); }
    static void Main() {
        Notification n = new Notification();
        n.OnNotify += ShowMessage;
        n.SendMessage();
    }
}
```

**Output**
```
Sending message...
Event triggered!
```

[⬆ Back to top](#top)

---

<a id="p4"></a>

## Program 4 — Method (function) overloading

**Question:** Write a C# program to demonstrate function/method overloading by creating multiple methods with the same name but different parameters.

```csharp
using System;
class Program {
    static int Add(int a, int b) { return a + b; }
    static int Add(int a, int b, int c) { return a + b + c; }
    static double Add(double a, double b) { return a + b; }
    static void Main() {
        Console.WriteLine(Add(10, 20));
        Console.WriteLine(Add(10, 20, 30));
        Console.WriteLine(Add(5.5, 4.5));
    }
}
```

**Output**
```
30
60
10
```

[⬆ Back to top](#top)

---

<a id="p5"></a>

## Program 5 — Constructor overloading

**Question:** Write a C# program to demonstrate constructor overloading by defining multiple constructors with different parameter lists in the same class.

```csharp
using System;
class Student {
    string name;
    int age;
    public Student() { name = "Unknown"; age = 0; }
    public Student(string n) { name = n; age = 18; }
    public Student(string n, int a) { name = n; age = a; }
    public void Display() { Console.WriteLine(name + " " + age); }
}
class Program {
    static void Main() {
        Student s1 = new Student();
        Student s2 = new Student("Rahul");
        Student s3 = new Student("Amit", 20);
        s1.Display(); s2.Display(); s3.Display();
    }
}
```

**Output**
```
Unknown 0
Rahul 18
Amit 20
```

[⬆ Back to top](#top)

---

<a id="p6"></a>

## Program 6 — Single inheritance

**Question:** Write a C# program to demonstrate Single Inheritance using a base class and a derived class.

```csharp
using System;
class Animal {
    public void Eat() { Console.WriteLine("Animal eats food"); }
}
class Dog : Animal {
    public void Bark() { Console.WriteLine("Dog barks"); }
}
class Program {
    static void Main() {
        Dog d = new Dog();
        d.Eat(); d.Bark();
    }
}
```

**Output**
```
Animal eats food
Dog barks
```

[⬆ Back to top](#top)

---

<a id="p7"></a>

## Program 7 — Multilevel inheritance

**Question:** Write a C# program to demonstrate Multilevel Inheritance using suitable classes and objects.

```csharp
using System;
class Animal {
    public void Eat() { Console.WriteLine("Animal eats"); }
}
class Dog : Animal {
    public void Bark() { Console.WriteLine("Dog barks"); }
}
class Puppy : Dog {
    public void Weep() { Console.WriteLine("Puppy weeps"); }
}
class Program {
    static void Main() {
        Puppy p = new Puppy();
        p.Eat(); p.Bark(); p.Weep();
    }
}
```

**Output**
```
Animal eats
Dog barks
Puppy weeps
```

[⬆ Back to top](#top)

---

<a id="p8"></a>

## Program 8 — Any two types of inheritance

**Question:** Write a C# program to demonstrate any two types of inheritance.

```csharp
using System;
class Animal {
    public void Eat() { Console.WriteLine("Animal eats"); }
}
class Dog : Animal {
    public void Bark() { Console.WriteLine("Dog barks"); }
}
class Cat : Animal {
    public void Meow() { Console.WriteLine("Cat meows"); }
}
class Program {
    static void Main() {
        Dog d = new Dog(); Cat c = new Cat();
        Console.WriteLine("Single Inheritance:");
        d.Eat(); d.Bark();
        Console.WriteLine("Hierarchical Inheritance:");
        c.Eat(); c.Meow();
    }
}
```

**Output**
```
Single Inheritance:
Animal eats
Dog barks
Hierarchical Inheritance:
Animal eats
Cat meows
```

[⬆ Back to top](#top)

---

<a id="p9"></a>

## Program 9 — Single, Multilevel and Hierarchical inheritance

**Question:** Write a C# program to demonstrate the different types of inheritance: Single, Multilevel, and Hierarchical.

```csharp
using System;
class Animal {
    public void Eat() { Console.WriteLine("Animal eats"); }
}
class Dog : Animal {
    public void Bark() { Console.WriteLine("Dog barks"); }
}
class Puppy : Dog {
    public void Weep() { Console.WriteLine("Puppy weeps"); }
}
class Cat : Animal {
    public void Meow() { Console.WriteLine("Cat meows"); }
}
class Program {
    static void Main() {
        Dog d = new Dog(); Puppy p = new Puppy();
        Cat c = new Cat();
        Console.WriteLine("Single Inheritance:");
        d.Eat(); d.Bark();
        Console.WriteLine("Multilevel Inheritance:");
        p.Eat(); p.Bark(); p.Weep();
        Console.WriteLine("Hierarchical Inheritance:");
        c.Eat(); c.Meow();
    }
}
```

**Output**
```
Single Inheritance:
Animal eats
Dog barks
Multilevel Inheritance:
Animal eats
Dog barks
Puppy weeps
Hierarchical Inheritance:
Animal eats
Cat meows
```

[⬆ Back to top](#top)

---

<a id="p10"></a>

## Program 10 — Multiple inheritance using interfaces

**Question:** Write a C# program to demonstrate multiple inheritance using interfaces. Define `IPrint` and `IShow` and implement them in a single class named `Demo`.

```csharp
using System;
interface IPrint { void Print(); }
interface IShow { void Show(); }
class Demo : IPrint, IShow {
    public void Print() { Console.WriteLine("Print method called"); }
    public void Show() { Console.WriteLine("Show method called"); }
}
class Program {
    static void Main() {
        Demo d = new Demo();
        d.Print(); d.Show();
    }
}
```

**Output**
```
Print method called
Show method called
```

[⬆ Back to top](#top)

---

<a id="p11"></a>

## Program 11 — Interface as a contract

**Question:** Write a C# program to demonstrate the use of interfaces by defining contracts that classes must implement.

```csharp
using System;
interface IVehicle {
    void Start();
    void Stop();
}
class Car : IVehicle {
    public void Start() { Console.WriteLine("Car started"); }
    public void Stop() { Console.WriteLine("Car stopped"); }
}
class Program {
    static void Main() {
        Car c = new Car();
        c.Start(); c.Stop();
    }
}
```

**Output**
```
Car started
Car stopped
```

[⬆ Back to top](#top)

---

<a id="p12"></a>

## Program 12 — IShape (Circle and Rectangle)

**Question:** Create an interface `IShape` containing a method `CalculateArea()`. Implement the interface in `Circle` and `Rectangle` classes and display their respective areas.

```csharp
using System;
interface IShape { double CalculateArea(); }
class Circle : IShape {
    double radius = 5;
    public double CalculateArea() { return 3.14 * radius * radius; }
}
class Rectangle : IShape {
    double length = 10, breadth = 5;
    public double CalculateArea() { return length * breadth; }
}
class Program {
    static void Main() {
        Circle c = new Circle(); Rectangle r = new Rectangle();
        Console.WriteLine("Circle Area: " + c.CalculateArea());
        Console.WriteLine("Rectangle Area: " + r.CalculateArea());
    }
}
```

**Output**
```
Circle Area: 78.5
Rectangle Area: 50
```

[⬆ Back to top](#top)

---

<a id="p13"></a>

## Program 13 — BankAccount with Balance validation

**Question:** Create a `BankAccount` class with `AccountNumber` and `Balance` properties. Implement validation to ensure that the balance cannot be negative.

```csharp
using System;
class BankAccount {
    public int AccountNumber { get; set; }
    private double balance;
    public double Balance {
        get { return balance; }
        set {
            if (value >= 0) balance = value;
            else Console.WriteLine("Balance cannot be negative");
        }
    }
}
class Program {
    static void Main() {
        BankAccount b = new BankAccount();
        b.AccountNumber = 101;
        b.Balance = 5000;
        Console.WriteLine("Account Number: " + b.AccountNumber);
        Console.WriteLine("Balance: " + b.Balance);
        b.Balance = -1000;
        Console.WriteLine("Final Balance: " + b.Balance);
    }
}
```

**Output**
```
Account Number: 101
Balance: 5000
Balance cannot be negative
Final Balance: 5000
```

[⬆ Back to top](#top)

---

<a id="p14"></a>

## Program 14 — try-catch-finally (divide by zero)

**Question:** Write a C# program to demonstrate exception handling using try-catch-finally blocks. Handle the exception that occurs when a number is divided by zero.

```csharp
using System;
class Program {
    static void Main() {
        try {
            int a = 10, b = 0;
            int result = a / b;
            Console.WriteLine(result);
        }
        catch (DivideByZeroException) {
            Console.WriteLine("Cannot divide by zero");
        }
        finally {
            Console.WriteLine("Finally block executed");
        }
    }
}
```

**Output**
```
Cannot divide by zero
Finally block executed
```

[⬆ Back to top](#top)

---

<a id="p15"></a>

## Program 15 — Custom exception and multiple catch blocks

**Question:** Write a C# program to demonstrate exception handling using try-catch-finally blocks, custom exceptions, and multiple catch handlers.

```csharp
using System;
class InvalidAgeException : Exception {
    public InvalidAgeException(string message) : base(message) { }
}
class Program {
    static void Main() {
        try {
            Console.Write("Enter age: ");
            int age = int.Parse(Console.ReadLine());
            if (age < 18)
                throw new InvalidAgeException("Age must be 18 or above");
            Console.WriteLine("Eligible");
        }
        catch (InvalidAgeException ex) {
            Console.WriteLine(ex.Message);
        }
        catch (FormatException) {
            Console.WriteLine("Invalid input");
        }
        catch (Exception ex) {
            Console.WriteLine(ex.Message);
        }
        finally { Console.WriteLine("Program completed"); }
    }
}
```

**Output**
```
Enter age: 16
Age must be 18 or above
Program completed
```
Other inputs: `20` → `Eligible`; `abc` → `Invalid input` (both followed by `Program completed`).

[⬆ Back to top](#top)

---

<a id="p16"></a>

## Program 16 — Pascal's triangle

**Question:** Write a C# program to accept the number of rows from the user and display Pascal's triangle using nested loops.

```csharp
using System;
class Program {
    static void Main() {
        Console.Write("Enter number of rows: ");
        int n = int.Parse(Console.ReadLine());
        for (int i = 0; i < n; i++) {
            long num = 1;
            for (int j = 0; j < n - i - 1; j++)
                Console.Write(" ");
            for (int j = 0; j <= i; j++) {
                Console.Write(num + " ");
                if (j < i) num = num * (i - j) / (j + 1);
            }
            Console.WriteLine();
        }
    }
}
```

**Output**
```
Enter number of rows: 5
    1
   1 1
  1 2 1
 1 3 3 1
1 4 6 4 1
```

[⬆ Back to top](#top)

---

<a id="p17"></a>

## Program 17 — Floyd's triangle

**Question:** Write a C# program to print Floyd's triangle up to N rows, where N is input by the user.

```csharp
using System;
class Program {
    static void Main() {
        Console.Write("Enter number of rows: ");
        int n = int.Parse(Console.ReadLine());
        int num = 1;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                Console.Write(num + " ");
                num++;
            }
            Console.WriteLine();
        }
    }
}
```

**Output**
```
Enter number of rows: 5
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

[⬆ Back to top](#top)

---

<a id="p18"></a>

## Program 18 — Sort 10 city names

**Question:** Write C# code to accept the names of 10 cities from the user and arrange the city names in sorted order.

```csharp
using System;
class Program {
    static void Main() {
        string[] cities = new string[10];
        Console.WriteLine("Enter 10 city names:");
        for (int i = 0; i < 10; i++)
            cities[i] = Console.ReadLine();
        Array.Sort(cities, StringComparer.OrdinalIgnoreCase);
        Console.WriteLine("Sorted City Names:");
        foreach (string city in cities)
            Console.WriteLine(city);
    }
}
```

**Output**
```
Enter 10 city names:
Pune
Mumbai
Delhi
Chennai
Kolkata
Nagpur
Nashik
Jaipur
Surat
Bangalore
Sorted City Names:
Bangalore
Chennai
Delhi
Jaipur
Kolkata
Mumbai
Nagpur
Nashik
Pune
Surat
```

[⬆ Back to top](#top)

---

<a id="p19"></a>

## Program 19 — Console arithmetic application

**Question:** Create a C# application to perform basic arithmetic operations.

```csharp
using System;
class Program {
    static void Main() {
        Console.Write("Enter first number: ");
        double a = Convert.ToDouble(Console.ReadLine());
        Console.Write("Enter second number: ");
        double b = Convert.ToDouble(Console.ReadLine());
        Console.WriteLine("1. Addition");
        Console.WriteLine("2. Subtraction");
        Console.WriteLine("3. Multiplication");
        Console.WriteLine("4. Division");
        Console.Write("Enter choice: ");
        int choice = Convert.ToInt32(Console.ReadLine());
        switch (choice) {
            case 1: Console.WriteLine("Result: " + (a + b)); break;
            case 2: Console.WriteLine("Result: " + (a - b)); break;
            case 3: Console.WriteLine("Result: " + (a * b)); break;
            case 4:
                if (b != 0) Console.WriteLine("Result: " + (a / b));
                else Console.WriteLine("Cannot divide by zero");
                break;
            default: Console.WriteLine("Invalid choice"); break;
        }
    }
}
```

**Output**
```
Enter first number: 20
Enter second number: 10
1. Addition
2. Subtraction
3. Multiplication
4. Division
Enter choice: 1
Result: 30
```

[⬆ Back to top](#top)

---

<a id="section-b"></a>

# B. ASP.NET MVC, Web Forms and Core

---

## ASP.NET Core MVC (Q20 – Q22)

*Run type: **ASP.NET Core Web App (MVC)**, project name `Demo` — see [MVC steps](#how-to-run).*

---

<a id="p20"></a>

### Program 20 — MVC: two numbers, four operations (with Model)

**Question:** Develop an ASP.NET MVC application that accepts two numbers from the user, performs addition, subtraction, multiplication, and division, and displays the results on the webpage.

**Models/Calc.cs**
```csharp
namespace Demo.Models;
public class Calc
{
    public double A { get; set; }
    public double B { get; set; }
}
```

**Controllers/CalcController.cs**
```csharp
using Microsoft.AspNetCore.Mvc;
using Demo.Models;
namespace Demo.Controllers;
public class CalcController : Controller
{
    [HttpGet] public IActionResult Index() => View(new Calc());
    [HttpPost] public IActionResult Index(Calc m)
    {
        ViewBag.Add = m.A + m.B;
        ViewBag.Sub = m.A - m.B;
        ViewBag.Mul = m.A * m.B;
        ViewBag.Div = m.B == 0 ? "Undefined" : (m.A / m.B).ToString();
        return View(m);
    }
}
```

**Views/Calc/Index.cshtml**
```html
@model Demo.Models.Calc
<form method="post">
    <input asp-for="A" type="number" step="any" />
    <input asp-for="B" type="number" step="any" />
    <button type="submit">Calculate</button>
</form>
@if (ViewBag.Add != null) {
    <p>Add: @ViewBag.Add</p><p>Subtract: @ViewBag.Sub</p>
    <p>Multiply: @ViewBag.Mul</p><p>Divide: @ViewBag.Div</p>
}
```

**Output** — URL `/Calc`: Input `A=20, B=10` → `Add: 30; Subtract: 10; Multiply: 200; Divide: 2`

[⬆ Back to top](#top)

---

<a id="p21"></a>

### Program 21 — MVC: square and cube

**Question:** Develop an ASP.NET MVC application that accepts a number from the user and finds its square and cube. Display the results on the webpage.

**Controllers/NumberController.cs**
```csharp
using Microsoft.AspNetCore.Mvc;
namespace Demo.Controllers;
public class NumberController : Controller
{
    [HttpGet] public IActionResult Index() => View();
    [HttpPost] public IActionResult Index(double number)
    {
        ViewBag.Square = number * number;
        ViewBag.Cube = number * number * number;
        return View();
    }
}
```

**Views/Number/Index.cshtml**
```html
<form method="post">
    <input type="number" step="any" name="number" required />
    <button type="submit">Find</button>
</form>
@if (ViewBag.Square != null) {
    <p>Square: @ViewBag.Square</p>
    <p>Cube: @ViewBag.Cube</p>
}
```

**Output** — URL `/Number`: Input `5` → `Square: 25; Cube: 125`

[⬆ Back to top](#top)

---

<a id="p22"></a>

### Program 22 — MVC: basic arithmetic operations

**Question:** Create an MVC application to perform basic arithmetic operations.

**Controllers/CalculatorController.cs**
```csharp
using Microsoft.AspNetCore.Mvc;
namespace Demo.Controllers;
public class CalculatorController : Controller
{
    [HttpGet] public IActionResult Index() => View();
    [HttpPost] public IActionResult Index(double a, double b, string op)
    {
        ViewBag.Result = op switch
        {
            "+" => (a + b).ToString(),
            "-" => (a - b).ToString(),
            "*" => (a * b).ToString(),
            "/" when b != 0 => (a / b).ToString(),
            "/" => "Cannot divide by zero",
            _ => "Invalid operation"
        };
        return View();
    }
}
```

**Views/Calculator/Index.cshtml**
```html
<form method="post">
    <input name="a" type="number" step="any" required />
    <input name="b" type="number" step="any" required />
    <select name="op">
        <option>+</option><option>-</option><option>*</option><option>/</option>
    </select>
    <button type="submit">Calculate</button>
</form>
<p>@ViewBag.Result</p>
```

**Output** — URL `/Calculator`: Input `12, 4, *` → `48`

[⬆ Back to top](#top)

---

## ASP.NET Web Forms (Q23 – Q30)

*Run type: **ASP.NET Web Application (.NET Framework) → Web Forms** — see [Web Forms steps](#how-to-run). In a Web Application project use `CodeBehind` instead of `CodeFile` in the Page directive.*

---

<a id="p23"></a>

### Program 23 — Student Registration Form

**Question:** Create an ASP.NET Web Forms Student Registration Form using Label, TextBox, RadioButton, DropDownList, CheckBox, Calendar, and Button controls. Display the submitted details using a Label control.

**Student.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Student.aspx.cs" Inherits="Student" %>
<form id="form1" runat="server">
    <asp:Label runat="server" Text="Name: " />
    <asp:TextBox ID="txtName" runat="server" /><br/>
    <asp:RadioButton ID="rbMale" runat="server" GroupName="Gender" Text="Male" />
    <asp:RadioButton ID="rbFemale" runat="server" GroupName="Gender" Text="Female" /><br/>
    <asp:DropDownList ID="ddlCourse" runat="server">
        <asp:ListItem>BSc IT</asp:ListItem>
        <asp:ListItem>BSc CS</asp:ListItem>
        <asp:ListItem>BCA</asp:ListItem>
    </asp:DropDownList><br/>
    <asp:CheckBox ID="chkTerms" runat="server" Text="I accept the Terms &amp; Conditions" /><br/>
    <asp:Calendar ID="calDate" runat="server" /><br/>
    <asp:Button runat="server" Text="Register" OnClick="Submit_Click" /><br/>
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Student.aspx.cs**
```csharp
using System;
using System.Web.UI;
public partial class Student : Page
{
    protected void Submit_Click(object sender, EventArgs e)
    {
        if (!chkTerms.Checked)
        {
            lblResult.Text = "Please accept the Terms & Conditions.";
            return;
        }
        string gender = rbMale.Checked ? "Male" : rbFemale.Checked ? "Female" : "Not selected";
        string date = calDate.SelectedDate == DateTime.MinValue
            ? "Not selected" : calDate.SelectedDate.ToShortDateString();
        lblResult.Text = "Name: " + Server.HtmlEncode(txtName.Text) +
            "; Gender: " + gender + "; Course: " + ddlCourse.SelectedValue +
            "; Terms accepted: " + chkTerms.Checked + "; Date: " + date;
    }
}
```

**Output**
```
Name: Riya; Gender: Female; Course: BCA; Terms accepted: True; Date: 10/28/2026
```
*Select a date in the Calendar before submitting.*

[⬆ Back to top](#top)

---

<a id="p24"></a>

### Program 24 — Employee Registration Form

**Question:** Create an ASP.NET Web Forms Employee Registration Form using Label, TextBox, RadioButton, DropDownList, CheckBox, Calendar, and Button controls. Display the submitted details using a Label control.

**Employee.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Employee.aspx.cs" Inherits="Employee" %>
<form id="form1" runat="server">
    <asp:Label runat="server" Text="Name" />
    <asp:TextBox ID="txtName" runat="server" /><br/>
    <asp:RadioButton ID="rbMale" runat="server" GroupName="Gender" Text="Male" />
    <asp:RadioButton ID="rbFemale" runat="server" GroupName="Gender" Text="Female" /><br/>
    <asp:DropDownList ID="ddlDepartment" runat="server">
        <asp:ListItem>HR</asp:ListItem><asp:ListItem>IT</asp:ListItem>
    </asp:DropDownList><br/>
    <asp:CheckBox ID="chkFullTime" runat="server" Text="Full Time" /><br/>
    <asp:Calendar ID="calDate" runat="server" /><br/>
    <asp:Button runat="server" Text="Save" OnClick="Submit_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Employee.aspx.cs**
```csharp
using System;
using System.Web.UI;
public partial class Employee : Page
{
    protected void Submit_Click(object sender, EventArgs e)
    {
        string gender = rbMale.Checked ? "Male" : rbFemale.Checked ? "Female" : "Not selected";
        lblResult.Text = Server.HtmlEncode(txtName.Text) + ", " + gender +
            ", " + ddlDepartment.SelectedValue + ", Full Time: " + chkFullTime.Checked +
            ", Joining Date: " + calDate.SelectedDate.ToShortDateString();
    }
}
```

**Output**
```
Aman, Male, IT, Full Time: True, Joining Date: 10/28/2026
```

[⬆ Back to top](#top)

---

<a id="p25"></a>

### Program 25 — Student Feedback Form

**Question:** Write an ASP.NET Web Forms program to design a Student Feedback Form using TextBox, RadioButton, CheckBox, DropDownList, and Button controls.

**Feedback.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Feedback.aspx.cs" Inherits="Feedback" %>
<form runat="server">
    <asp:TextBox ID="txtName" runat="server" /><br/>
    <asp:RadioButton ID="rbGood" runat="server" Text="Good" GroupName="Rating" />
    <asp:RadioButton ID="rbPoor" runat="server" Text="Poor" GroupName="Rating" /><br/>
    <asp:CheckBox ID="chkRecommend" runat="server" Text="Recommend" /><br/>
    <asp:DropDownList ID="ddlSubject" runat="server">
        <asp:ListItem>C#</asp:ListItem><asp:ListItem>ASP.NET</asp:ListItem>
    </asp:DropDownList><br/>
    <asp:TextBox ID="txtComments" runat="server" TextMode="MultiLine" /><br/>
    <asp:Button runat="server" Text="Submit" OnClick="Submit_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Feedback.aspx.cs**
```csharp
using System;
using System.Web.UI;
public partial class Feedback : Page
{
    protected void Submit_Click(object sender, EventArgs e)
    {
        string rating = rbGood.Checked ? "Good" : rbPoor.Checked ? "Poor" : "None";
        lblResult.Text = Server.HtmlEncode(txtName.Text) + ": " + rating +
            ", Subject: " + ddlSubject.SelectedValue +
            ", Recommend: " + chkRecommend.Checked +
            ", Comments: " + Server.HtmlEncode(txtComments.Text);
    }
}
```

**Output**
```
Riya: Good, Subject: C#, Recommend: True, Comments: Useful class
```

[⬆ Back to top](#top)

---

<a id="p26"></a>

### Program 26 — Registration form with validation controls

**Question:** Create an ASP.NET Web Forms Registration Form using RequiredFieldValidator, RangeValidator, RegularExpressionValidator, and CompareValidator controls.

**Validation.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Validation.aspx.cs" Inherits="Validation" %>
<form runat="server">
    Name: <asp:TextBox ID="txtName" runat="server" />
    <asp:RequiredFieldValidator runat="server" ControlToValidate="txtName"
        ErrorMessage="Name required" ForeColor="Red" /><br/>
    Age: <asp:TextBox ID="txtAge" runat="server" />
    <asp:RangeValidator runat="server" ControlToValidate="txtAge"
        Type="Integer" MinimumValue="18" MaximumValue="60"
        ErrorMessage="Age must be 18 to 60" ForeColor="Red" /><br/>
    Email: <asp:TextBox ID="txtEmail" runat="server" />
    <asp:RegularExpressionValidator runat="server" ControlToValidate="txtEmail"
        ValidationExpression="^[^@\s]+@[^@\s]+\.[^@\s]+$"
        ErrorMessage="Invalid email" ForeColor="Red" /><br/>
    Password: <asp:TextBox ID="txtPass" runat="server" TextMode="Password" /><br/>
    Confirm: <asp:TextBox ID="txtConfirm" runat="server" TextMode="Password" />
    <asp:CompareValidator runat="server" ControlToValidate="txtConfirm"
        ControlToCompare="txtPass" ErrorMessage="Passwords differ" ForeColor="Red" /><br/>
    <asp:Button runat="server" Text="Submit" OnClick="Submit_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Validation.aspx.cs**
```csharp
using System;
using System.Web.UI;
public partial class Validation : Page
{
    protected void Submit_Click(object sender, EventArgs e)
    {
        if (Page.IsValid) lblResult.Text = "Registration successful";
    }
}
```

**Output**
```
Valid details   → Registration successful
Invalid age     → Age must be 18 to 60
```
> Note: for production, also add `RequiredFieldValidator`s for Age, Email and Password.
> If Visual Studio shows a *"WebForms UnobtrusiveValidationMode"* error, add this to `Web.config` → `<appSettings>`:
> `<add key="ValidationSettings:UnobtrusiveValidationMode" value="None" />`

[⬆ Back to top](#top)

---

<a id="p27"></a>

### Program 27 — Validated Student Registration

**Question:** Write an ASP.NET Web Forms program to validate student registration details and display the submitted information using appropriate controls.

**StudentValidated.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="StudentValidated.aspx.cs" Inherits="StudentValidated" %>
<form runat="server">
    Name: <asp:TextBox ID="txtName" runat="server" />
    <asp:RequiredFieldValidator runat="server" ControlToValidate="txtName" ErrorMessage="Required" /><br/>
    Age: <asp:TextBox ID="txtAge" runat="server" />
    <asp:RequiredFieldValidator runat="server" ControlToValidate="txtAge" ErrorMessage="Required" />
    <asp:RangeValidator runat="server" ControlToValidate="txtAge" Type="Integer"
        MinimumValue="16" MaximumValue="100" ErrorMessage="Invalid age" /><br/>
    Course: <asp:DropDownList ID="ddlCourse" runat="server">
        <asp:ListItem>BCA</asp:ListItem><asp:ListItem>BSc</asp:ListItem>
    </asp:DropDownList><br/>
    <asp:Button runat="server" Text="Submit" OnClick="Submit_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**StudentValidated.aspx.cs**
```csharp
using System;
using System.Web.UI;
public partial class StudentValidated : Page
{
    protected void Submit_Click(object sender, EventArgs e)
    {
        if (Page.IsValid)
            lblResult.Text = "Student: " + Server.HtmlEncode(txtName.Text) +
                ", Age: " + txtAge.Text + ", Course: " + ddlCourse.SelectedValue;
    }
}
```

**Output**
```
Student: Riya, Age: 20, Course: BCA
```

[⬆ Back to top](#top)

---

<a id="p28"></a>

### Program 28 — AdRotator

**Question:** Create an ASP.NET Web Forms application that displays rotating advertisements using the AdRotator control and an advertisement XML file.

**Ads.aspx**
```aspx
<%@ Page Language="C#" %>
<form runat="server">
    <asp:AdRotator ID="AdRotator1" runat="server"
        AdvertisementFile="~/Ads.xml" Target="_blank" />
</form>
```

**Ads.xml**
```xml
<?xml version="1.0" encoding="utf-8" ?>
<Advertisements>
  <Ad>
    <ImageUrl>~/Images/ad1.png</ImageUrl>
    <NavigateUrl>https://example.com/offer1</NavigateUrl>
    <AlternateText>Offer One</AlternateText>
    <Impressions>50</Impressions>
  </Ad>
  <Ad>
    <ImageUrl>~/Images/ad2.png</ImageUrl>
    <NavigateUrl>https://example.com/offer2</NavigateUrl>
    <AlternateText>Offer Two</AlternateText>
    <Impressions>50</Impressions>
  </Ad>
</Advertisements>
```

**Output:** the page shows one advertisement image; refreshing may show the other.
*Place `ad1.png` and `ad2.png` in an `Images` folder; replace example URLs with real ones.*

[⬆ Back to top](#top)

---

<a id="p29"></a>

### Program 29 — Session cookies and persistent cookies

**Question:** Develop a web application to demonstrate session cookies and persistent cookies. Store and retrieve user information using cookies.

**Cookies.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Cookies.aspx.cs" Inherits="Cookies" %>
<form runat="server">
    <asp:TextBox ID="txtUser" runat="server" />
    <asp:Button runat="server" Text="Save" OnClick="Save_Click" />
    <asp:Button runat="server" Text="Read" OnClick="Read_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Cookies.aspx.cs**
```csharp
using System;
using System.Web;
using System.Web.UI;
public partial class Cookies : Page
{
    protected void Save_Click(object sender, EventArgs e)
    {
        Response.Cookies.Add(new HttpCookie("SessionUser", txtUser.Text)
            { HttpOnly = true, Secure = Request.IsSecureConnection });
        Response.Cookies.Add(new HttpCookie("SavedUser", txtUser.Text)
            { Expires = DateTime.Now.AddDays(7), HttpOnly = true,
              Secure = Request.IsSecureConnection });
        lblResult.Text = "Cookies saved. Click Read on the next request.";
    }
    protected void Read_Click(object sender, EventArgs e)
    {
        string a = Request.Cookies["SessionUser"]?.Value ?? "Missing";
        string b = Request.Cookies["SavedUser"]?.Value ?? "Missing";
        lblResult.Text = "Session: " + Server.HtmlEncode(a) +
            "; Persistent: " + Server.HtmlEncode(b);
    }
}
```

**Output:** Enter `Riya` → **Save** → **Read** → `Session: Riya; Persistent: Riya`

> Use HTTPS in production; never store passwords or sensitive data in cookies.

[⬆ Back to top](#top)

---

<a id="p30"></a>

### Program 30 — Different types of cookies

**Question:** Create a web application to demonstrate the use of different types of cookies.

**Types.aspx**
```aspx
<%@ Page Language="C#" AutoEventWireup="true" CodeFile="Types.aspx.cs" Inherits="Types" %>
<form runat="server">
    <asp:Button runat="server" Text="Create Cookies" OnClick="Create_Click" />
    <asp:Button runat="server" Text="Show Cookies" OnClick="Show_Click" />
    <asp:Label ID="lblResult" runat="server" />
</form>
```

**Types.aspx.cs**
```csharp
using System;
using System.Web;
using System.Web.UI;
public partial class Types : Page
{
    protected void Create_Click(object sender, EventArgs e)
    {
        Response.Cookies.Add(new HttpCookie("Theme", "Dark") { HttpOnly = true });
        Response.Cookies.Add(new HttpCookie("Language", "English")
            { Expires = DateTime.Now.AddMonths(1), HttpOnly = true });
        lblResult.Text = "Session and persistent cookies created";
    }
    protected void Show_Click(object sender, EventArgs e)
    {
        lblResult.Text = "Theme: " + (Request.Cookies["Theme"]?.Value ?? "None") +
            "; Language: " + (Request.Cookies["Language"]?.Value ?? "None");
    }
}
```

**Output:** **Create** then **Show** → `Theme: Dark; Language: English`
*`Theme` is a session cookie (no expiry); `Language` is a persistent cookie (expires in 1 month).*

[⬆ Back to top](#top)

---

## ASP.NET Core (Q31 – Q33)

*Run type: **ASP.NET Core Empty** — see [minimal API steps](#how-to-run). Each program is a separate project.*

---

<a id="p31"></a>

### Program 31 — Role-based authentication (Admin / User)

**Question:** Develop an ASP.NET Core web application to authenticate users and restrict access to pages based on user roles, such as Admin and User.

**Program.cs**
```csharp
using Microsoft.AspNetCore.Authentication.Cookies;
using System.Security.Claims;
using Microsoft.AspNetCore.Authentication;

var builder = WebApplication.CreateBuilder(args);
builder.Services.AddAuthentication("Cookies").AddCookie("Cookies", o =>
{
    o.LoginPath = "/login";
    o.AccessDeniedPath = "/denied";
});
builder.Services.AddAuthorization();
var app = builder.Build();
app.UseAuthentication();
app.UseAuthorization();

app.MapGet("/login", () => Results.Content(
    "POST /login with username and password", "text/plain"));

app.MapPost("/login", async (HttpContext ctx, LoginRequest req) =>
{
    // Demo only: replace with a user database and hashed passwords.
    string? role = req.Username == "admin" && req.Password == "Admin123!"
        ? "Admin" : req.Username == "user" && req.Password == "User123!"
        ? "User" : null;
    if (role == null) return Results.Unauthorized();
    var claims = new[] { new Claim(ClaimTypes.Name, req.Username),
                         new Claim(ClaimTypes.Role, role) };
    await ctx.SignInAsync("Cookies", new ClaimsPrincipal(
        new ClaimsIdentity(claims, "Cookies")));
    return Results.Ok("Signed in as " + role);
});

app.MapGet("/admin", () => "Admin page").RequireAuthorization(
    new Microsoft.AspNetCore.Authorization.AuthorizeAttribute { Roles = "Admin" });
app.MapGet("/user", () => "User page").RequireAuthorization(
    new Microsoft.AspNetCore.Authorization.AuthorizeAttribute { Roles = "User,Admin" });
app.MapGet("/denied", () => Results.Text("Access denied"));
app.Run();

record LoginRequest(string Username, string Password);
```

**Test in Postman**
```
POST https://localhost:xxxx/login      Body (raw JSON): {"username":"admin","password":"Admin123!"}
→ Signed in as Admin
GET  https://localhost:xxxx/admin      → Admin page
```
> Educational demo only. Never hardcode credentials; use ASP.NET Core Identity, HTTPS and antiforgery protection in production.

[⬆ Back to top](#top)

---

<a id="p32"></a>

### Program 32 — Authentication and Authorization

**Question:** Create an ASP.NET Core application to demonstrate Authentication and Authorization.

**Program.cs**
```csharp
using Microsoft.AspNetCore.Authentication;
using Microsoft.AspNetCore.Authentication.Cookies;
using System.Security.Claims;

var builder = WebApplication.CreateBuilder(args);
builder.Services.AddAuthentication("Cookies").AddCookie("Cookies");
builder.Services.AddAuthorization();
var app = builder.Build();
app.UseAuthentication();
app.UseAuthorization();

app.MapGet("/signin", async (HttpContext ctx) =>
{
    var identity = new ClaimsIdentity(new[] {
        new Claim(ClaimTypes.Name, "DemoStudent") }, "Cookies");
    await ctx.SignInAsync("Cookies", new ClaimsPrincipal(identity));
    return "Authenticated";
});
app.MapGet("/public", () => "Public page");
app.MapGet("/private", (ClaimsPrincipal user) =>
    "Welcome " + user.Identity!.Name).RequireAuthorization();
app.MapGet("/signout", async (HttpContext ctx) =>
{
    await ctx.SignOutAsync("Cookies");
    return "Signed out";
});
app.Run();
```

**Output (browser)**
```
/public   → Public page
/private  → (redirects to login / 401 until signed in)
/signin   → Authenticated
/private  → Welcome DemoStudent
/signout  → Signed out
```

[⬆ Back to top](#top)

---

<a id="p33"></a>

### Program 33 — Web API returning student JSON

**Question:** Create a simple ASP.NET Core Web API that returns student details, such as Roll Number, Name, Course, and Marks, in JSON format. Test the endpoint using a browser or Postman.

**Program.cs**
```csharp
var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();
app.MapGet("/api/student", () => new Student(101, "Riya", "BCA", 85));
app.Run();

record Student(int RollNumber, string Name, string Course, int Marks);
```

**Output** — `GET /api/student`
```json
{"rollNumber":101,"name":"Riya","course":"BCA","marks":85}
```

[⬆ Back to top](#top)

---

<a id="section-c"></a>

# C. Progressive Web Applications (PWA)

*Run type: **ASP.NET Core Empty** serving static files from `wwwroot` — see [PWA steps](#how-to-run).*

## 🧩 Common PWA files (used by several programs)

Many PWA programs share the same `manifest.json` and `sw.js`. They are written once here; each program lists only what changes.

### Common `manifest.json`

Change only `name` and `short_name` per program (values are listed in each program).

```json
{
  "name": "APP NAME",
  "short_name": "SHORT NAME",
  "start_url": "./index.html",
  "scope": "./",
  "display": "standalone",
  "theme_color": "#174a7e",
  "background_color": "#ffffff",
  "icons": [
    {"src":"icon-192.png","sizes":"192x192","type":"image/png"},
    {"src":"icon-512.png","sizes":"512x512","type":"image/png"}
  ]
}
```

### Common `sw.js` (static cache, cache-then-network)

```javascript
const CACHE = 'pwa-static-v1';
const FILES = ['./', './index.html', './manifest.json',
               './icon-192.png', './icon-512.png'];

self.addEventListener('install', event => {
  event.waitUntil(caches.open(CACHE).then(c => c.addAll(FILES)));
  self.skipWaiting();
});
self.addEventListener('activate', event => {
  event.waitUntil(self.clients.claim());
});
self.addEventListener('fetch', event => {
  if (event.request.method !== 'GET') return;
  event.respondWith(
    caches.match(event.request).then(cached =>
      cached || fetch(event.request))
  );
});
```

### Common icon files
`icon-192.png` (192×192) and `icon-512.png` (512×512) — any square PNG images.

### How to test offline
1. Run the project (**F5**) and open the page once while online.
2. **F12 → Application → Service Workers** → confirm *activated and running*.
3. Tick **Offline** → reload → the page still opens.

[⬆ Back to top](#top)

---

<a id="p34"></a>

## Program 34 — College website PWA

**Question:** Develop a simple college website containing information about courses, faculty, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker.

**Files:** `index.html` (below) · `manifest.json` → `name: "ABC College"`, `short_name: "ABC College"` · `sw.js` → [common](#-common-pwa-files-used-by-several-programs)

**index.html**
```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>ABC College</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
<style>body{font:18px Arial;margin:30px;line-height:1.5}
section{padding:10px;border-bottom:1px solid #ccc}</style>
</head><body><h1>ABC College</h1>
<section><h2>Courses</h2><p>BCA, BSc Computer Science, BCom</p></section>
<section><h2>Faculty</h2><p>Prof. Sharma - Computer Science; Prof. Rao - Commerce</p></section>
<section><h2>Contact</h2><p>college@example.com | 020-12345678</p></section>
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body></html>
```

**Output**
```
ABC College
Courses: BCA, BSc Computer Science, BCom
Faculty: Prof. Sharma; Prof. Rao
Contact: college@example.com
Offline: previously cached homepage opens.
```

[⬆ Back to top](#top)

---

<a id="p35"></a>

## Program 35 — Company website PWA

**Question:** Develop a simple company website containing information about products, services, About Us, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker.

**Files:** `index.html` (below) · `manifest.json` → `name: "BrightTech Company"`, `short_name: "BrightTech"` · `sw.js` → [common](#-common-pwa-files-used-by-several-programs)

**index.html**
```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>BrightTech Company</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
<style>body{font:18px Arial;margin:30px;line-height:1.5}
section{padding:10px;border-bottom:1px solid #ccc}</style>
</head><body><h1>BrightTech Company</h1>
<section><h2>Products</h2><p>Laptop accessories and office software</p></section>
<section><h2>Services</h2><p>IT support and website development</p></section>
<section><h2>About Us</h2><p>Technology solutions for local businesses</p></section>
<section><h2>Contact</h2><p>hello@brighttech.example</p></section>
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body></html>
```

**Output**
```
BrightTech Company
Products: Laptop accessories and office software
Services: IT support and website development
About Us: Technology solutions for local businesses
Contact: hello@brighttech.example
Offline: cached homepage opens.
```

[⬆ Back to top](#top)

---

<a id="p36"></a>

## Program 36 — Hotel website PWA

**Question:** Develop a simple hotel website containing information about rooms, food, and contact details. Convert it into a PWA using a Web App Manifest and Service Worker.

**Files:** `index.html` (below) · `manifest.json` → `name: "Sunrise Hotel"`, `short_name: "Sunrise Hotel"` · `sw.js` → [common](#-common-pwa-files-used-by-several-programs)

**index.html**
```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Sunrise Hotel</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
<style>body{font:18px Arial;margin:30px;line-height:1.5}
section{padding:10px;border-bottom:1px solid #ccc}</style>
</head><body><h1>Sunrise Hotel</h1>
<section><h2>Rooms</h2><p>Standard, Deluxe and Suite rooms</p></section>
<section><h2>Food</h2><p>Breakfast, lunch and dinner available</p></section>
<section><h2>Contact</h2><p>booking@sunrise.example | 020-55550123</p></section>
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body></html>
```

**Output**
```
Sunrise Hotel
Rooms: Standard, Deluxe and Suite rooms
Food: Breakfast, lunch and dinner available
Contact: booking@sunrise.example
Offline: cached homepage opens.
```

[⬆ Back to top](#top)

---

<a id="p37"></a>

## Program 37 — College Information Portal PWA

**Question:** Develop a College Information Portal website and convert it into a Progressive Web Application (PWA) by implementing a Service Worker and Web App Manifest.

**Files:** `index.html` (below) · `manifest.json` → `name: "College Information Portal"`, `short_name: "College Info"` · `sw.js` → [common](#-common-pwa-files-used-by-several-programs)

**index.html**
```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>College Information Portal</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
<style>body{font:18px Arial;margin:30px;line-height:1.5}
section{padding:10px;border-bottom:1px solid #ccc}</style>
</head><body><h1>College Information Portal</h1>
<section><h2>Courses</h2><p>BCA, BBA and BSc</p></section>
<section><h2>Faculty</h2><p>Faculty directory and office hours</p></section>
<section><h2>Notices</h2><p>Semester exams begin 10 November</p></section>
<section><h2>Contact</h2><p>portal@college.example</p></section>
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body></html>
```

**Output**
```
College Information Portal
Courses: BCA, BBA and BSc
Faculty: Faculty directory and office hours
Notices: Semester exams begin 10 November
Contact: portal@college.example
Offline: cached portal opens.
```

[⬆ Back to top](#top)

---

<a id="p38"></a>

## Program 38 — Custom offline page

**Question:** Create a PWA that displays a custom offline page whenever the user loses internet connectivity. Use a Service Worker to cache the required resources.

**Files:** `index.html`, `offline.html`, `manifest.json` (`name: "Offline Demo"`, `short_name: "Offline Demo"`), `sw.js`

**index.html**
```html
<!DOCTYPE html><html><head><title>Offline Demo</title>
<link rel="manifest" href="manifest.json"></head>
<body><h1>Online Home Page</h1><p>Welcome to our PWA.</p>
<script>
if ('serviceWorker' in navigator)
  navigator.serviceWorker.register('./sw.js');
</script></body></html>
```

**offline.html**
```html
<!DOCTYPE html><html><body>
<h1>You are offline</h1>
<p>Please check your internet connection.</p>
</body></html>
```

**sw.js**
```javascript
const CACHE = 'offline-demo-v1';
self.addEventListener('install', event => {
  event.waitUntil(caches.open(CACHE).then(cache =>
    cache.addAll(['./index.html','./offline.html',
                  './manifest.json','./icon-192.png',
                  './icon-512.png'])));
  self.skipWaiting();
});
self.addEventListener('fetch', event => {
  if (event.request.mode === 'navigate') {
    event.respondWith(fetch(event.request).catch(() =>
      caches.match('./offline.html')));
  }
});
```

**Output**
```
With internet:    Online Home Page / Welcome to our PWA.
Without internet: You are offline / Please check your internet connection.
```
*Test: install the worker, tick **Offline** in DevTools, then reload.*

[⬆ Back to top](#top)

---

<a id="p39"></a>

## Program 39 — Cache-first PWA

**Question:** Develop a PWA that supports offline functionality using a Service Worker and the cache-first caching strategy.

**Files:** `index.html`, `manifest.json` (`name: "Cache First PWA"`, `short_name: "Cache First"`), `sw.js`

**index.html**
```html
<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Cache First PWA</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
<style>body{font:18px Arial;margin:30px;line-height:1.5}
section{padding:10px;border-bottom:1px solid #ccc}</style>
</head><body><h1>Cache First PWA</h1>
<section><h2>Message</h2><p>Cached content works offline.</p></section>
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body></html>
```

**sw.js**
```javascript
const CACHE = 'cache-first-v1';
const ASSETS = ['./','./index.html','./manifest.json',
                './icon-192.png','./icon-512.png'];

self.addEventListener('install', event => {
  event.waitUntil(caches.open(CACHE).then(c => c.addAll(ASSETS)));
  self.skipWaiting();
});
self.addEventListener('fetch', event => {
  if (event.request.method !== 'GET') return;
  event.respondWith(caches.match(event.request).then(hit => {
    return hit || fetch(event.request).then(response => {
      if (response.ok && new URL(event.request.url).origin ===
          self.location.origin) {
        const copy = response.clone();
        caches.open(CACHE).then(c => c.put(event.request, copy));
      }
      return response;
    });
  }));
});
```

**Output**
```
Online:  Cache First PWA / Cached content works offline.
Offline: the cached homepage still appears after reload.
```
> Cache-first can serve stale files — change the cache version (`cache-first-v2`) after updating assets.

[⬆ Back to top](#top)

---

<a id="p40"></a>

## Program 40 — Cache HTML, CSS, JS and images

**Question:** Develop a PWA that caches HTML, CSS, JavaScript, and image files using a Service Worker so that the application can work without an internet connection.

**Files:** `index.html`, `style.css`, `app.js`, `photo.png` (any image), `manifest.json` (`name: "Offline Assets"`, `short_name: "Offline Assets"`), `sw.js`

**index.html**
```html
<!DOCTYPE html><html><head><title>Offline Assets</title>
<link rel="manifest" href="manifest.json">
<link rel="stylesheet" href="style.css"></head>
<body><h1>Offline Asset Demo</h1><img src="photo.png" alt="Campus" width="200">
<p id="status"></p><script src="app.js"></script>
<script>if('serviceWorker' in navigator)
  navigator.serviceWorker.register('./sw.js');</script></body></html>
```

**style.css**
```css
body { font-family: Arial; background: #eef6ff; padding: 24px; }
h1 { color: #174a7e; }
```

**app.js**
```javascript
document.getElementById('status').textContent =
  'HTML, CSS, JavaScript and image loaded.';
```

**sw.js**
```javascript
const CACHE = 'all-assets-v1';
const FILES = ['./','./index.html','./style.css',
               './app.js','./photo.png','./manifest.json',
               './icon-192.png','./icon-512.png'];

self.addEventListener('install', event => {
  event.waitUntil(caches.open(CACHE).then(c => c.addAll(FILES)));
  self.skipWaiting();
});
self.addEventListener('fetch', event => {
  if (event.request.method === 'GET')
    event.respondWith(caches.match(event.request)
      .then(hit => hit || fetch(event.request)));
});
```

**Output**
```
Offline Asset Demo
[Campus image appears]
HTML, CSS, JavaScript and image loaded.
(The same page appears after going offline.)
```

[⬆ Back to top](#top)

---

<a id="p41"></a>

## Program 41 — HTML page linked to manifest.json

**Question:** Create an HTML page as the starting point of a PWA and link it to a `manifest.json` file for application configuration.

**Files:** `index.html` (below) · `manifest.json` → `name: "My First PWA"`, `short_name: "My First PWA"` · `sw.js` → [common](#-common-pwa-files-used-by-several-programs)

**index.html**
```html
<!DOCTYPE html><html lang="en"><head>
<meta charset="UTF-8"><meta name="viewport"
  content="width=device-width,initial-scale=1">
<title>My First PWA</title>
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#174a7e">
</head><body><h1>Welcome to My First PWA</h1>
<p>The page is linked to a Web App Manifest.</p>
<script>if ('serviceWorker' in navigator)
  navigator.serviceWorker.register('./sw.js');</script>
</body></html>
```

**Output**
```
Welcome to My First PWA
The page is linked to a Web App Manifest.
(Browser detects the manifest; the app can be installed when requirements are met.)
```

[⬆ Back to top](#top)

---

<a id="p42"></a>

## Program 42 — Configure manifest.json

**Question:** Create a `manifest.json` file and configure the application name, icons, start URL, theme color, background color, and display mode.

**manifest.json**
```json
{
  "name": "Student Information App",
  "short_name": "Student Info",
  "start_url": "./index.html",
  "scope": "./",
  "display": "standalone",
  "theme_color": "#174a7e",
  "background_color": "#ffffff",
  "icons": [
    {"src":"icon-192.png","sizes":"192x192","type":"image/png"},
    {"src":"icon-512.png","sizes":"512x512","type":"image/png"}
  ]
}
```

**Output** (shown in DevTools → Application → Manifest)
```
Name: Student Information App
Start URL: ./index.html
Theme color: #174a7e
Background color: #ffffff
Display: standalone
Icons: 192x192 and 512x512 PNG
```

[⬆ Back to top](#top)

---

<a id="p43"></a>

## Program 43 — Push notifications

**Question:** Create a PWA with a Web App Manifest file containing the app name, icons, start URL, and display mode. Implement push notifications in the PWA.

**Files:** `index.html`, `manifest.json` (`name: "Notification PWA"`, `short_name: "Notification"`), `app.js`, `sw.js`

**index.html**
```html
<!DOCTYPE html><html><head><title>Notify PWA</title>
<link rel="manifest" href="manifest.json"></head><body>
<h1>Push Notification PWA</h1>
<button id="enable">Enable Push</button>
<p id="status"></p><script src="app.js"></script>
</body></html>
```

**app.js**
```javascript
const statusEl = document.getElementById('status');
const regPromise = navigator.serviceWorker.register('./sw.js');

document.getElementById('enable').onclick = async () => {
  if (!('PushManager' in window)) {
    statusEl.textContent = 'Push not supported'; return;
  }
  const permission = await Notification.requestPermission();
  if (permission !== 'granted') {
    statusEl.textContent = 'Permission denied'; return;
  }
  const reg = await regPromise;
  // Replace this placeholder with a real public VAPID key.
  const publicKey = 'REPLACE_WITH_PUBLIC_VAPID_KEY';
  const keyBytes = urlBase64ToUint8Array(publicKey);
  const sub = await reg.pushManager.subscribe({
    userVisibleOnly: true, applicationServerKey: keyBytes
  });
  // Send the subscription to your push server for storage.
  await fetch('/subscribe', {method:'POST',
    headers:{'Content-Type':'application/json'},
    body:JSON.stringify(sub)});
  statusEl.textContent = 'Push subscription created';
};

function urlBase64ToUint8Array(base64) {
  const padded = base64.padEnd(Math.ceil(base64.length / 4)*4,'=')
                       .replace(/-/g,'+').replace(/_/g,'/');
  const raw = atob(padded);
  return Uint8Array.from(raw, c => c.charCodeAt(0));
}
```

**sw.js**
```javascript
self.addEventListener('push', event => {
  const data = event.data ? event.data.json() :
    {title:'New Update', body:'You have a notification'};
  event.waitUntil(self.registration.showNotification(
    data.title || 'New Update', {
      body: data.body || 'Open the app for details',
      icon: './icon-192.png'
    }));
});
self.addEventListener('notificationclick', event => {
  event.notification.close();
  event.waitUntil(clients.openWindow('./index.html'));
});
```

**Output**
```
Notification PWA
[Enable Push]
After a valid VAPID key and push backend are configured:
  Push subscription created
When the server sends a push → notification appears:
  New Update - Exam timetable published.
```
> This is the client side plus a server contract. Generate a VAPID key pair, replace the placeholder public key, and implement `POST /subscribe` and server-side Web Push sending. Requires HTTPS or localhost and the user's permission. Quick test without a server: **DevTools → Application → Service Workers → Push** button.

[⬆ Back to top](#top)

---

<a id="troubleshooting"></a>

## 🛠️ Troubleshooting

| Problem | Fix |
|---|---|
| `Console.ReadLine()` returns a nullable warning | Warnings only — the program still runs. |
| Web Forms template not visible | Install **ASP.NET and web development** workload and choose *ASP.NET Web Application (.NET Framework)*. |
| `CodeFile` / `Inherits` error | In a Web Application project use `CodeBehind="Page.aspx.cs"` and make the class name match the page. |
| Service worker not registering | Use `localhost` or HTTPS; check **F12 → Application → Service Workers**. |
| Old files still shown in PWA | Tick **Update on reload** or **Unregister** in DevTools, or bump the cache version (`v1` → `v2`). |
| Install button missing | Make sure both icons exist and `manifest.json` has no errors (DevTools → Application → Manifest). |
| Postman SSL error | Turn off *SSL certificate verification* in Postman settings (local testing only). |

---

## 📁 Suggested Repository Structure

```
├── README.md
├── A-CSharp-Console/        Q1–Q19
├── B1-ASPNET-MVC/           Q20–Q22
├── B2-ASPNET-WebForms/      Q23–Q30
├── B3-ASPNET-Core/          Q31–Q33
└── C-PWA/                   Q34–Q43
```

---

## 📜 License / Usage

For educational purposes. Feel free to fork, share and improve — pull requests are welcome.

[⬆ Back to top](#top)
