# 🐶🐱🦆 Hello World with Animals

A fun Java application demonstrating basic Object-Oriented Programming (OOP) by creating custom animal classes (`Dog`, `Cat`, `Duck`) and invoking their unique sound methods! 🔊✨

---

## 📌 Features 🌟

* **🐕 Dog Class:** Outputs a dog barking sound (`Arf! Arf! Arf!`).
* **🐈 Cat Class:** Outputs a cat meowing sound (`Meow! Meow`).
* **🦆 Duck Class:** Outputs a duck quacking sound (`Quack! Quack!`).
* **🎮 Main Driver:** Instantiates each animal object and triggers their `sayHello()` method in sequence.

---

## 💡 Code Overview 💻

```java
class Dog {
    public void sayHello() {
        System.out.println("Arf! Arf! Arf!");
    }
}

class Cat {
    public void sayHello() {
        System.out.println("Meow! Meow");
    }
}

class Duck {
    public void sayHello() {
        System.out.println("Quack! Quack!");
    }
}

public class HelloWorldwithAnimals {
    public static void main(String[] args) {

        Dog animal1 = new Dog();
        Cat animal2 = new Cat();
        Duck animal3 = new Duck();
        
        animal1.sayHello();
        animal2.sayHello();
        animal3.sayHello();
    }
}