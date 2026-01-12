# Chapter 1: Getting Started with C#

- [1.1 Introduction to C#](#11-introduction-to-kafka-and-event-streaming)
- [1.2 Kafka in Modern Architecture](#12-kafka-in-modern-architecture)
- [1.3 Kafka Ecosystem Overview](#13-kafka-ecosystem-overview)
- [1.4 Kafka vs RabbitMQ vs MQTT vs Azure Event Hubs](#14-kafka-vs-rabbitmq-vs-mqtt-vs-azure-event-hubs)

---

## 1.1 Introduction to C#

### Introduction

C# is a object-oriented programming language developed by Microsoft. It is widely used to build Windows applications, web applications, mobile apps, games (using Unity), and enterprise software systems.

C# runs on the .NET runtime, which allows applications to execute on multiple platforms including Windows, macOS, and Linux with .NET Core and later versions of .NET. Its syntax is similar to other C-based languages like C++ and Java.

### Why use C#?
- **Easy to learn:** Clear, readable syntax, familiar to Java/C++ developers.
- **Object-Oriented:** Supports OOP principles (encapsulation, inheritance, polymorphism).
- **Cross-platform:** Build desktop, web, mobile, cloud and game applications.
- **Rich libraries & frameworks:** Large .NET library for faster development.
- **Memory management:** Automatic garbage collection reduces memory leaks.
- **Modern features:** LINQ, async/await and other powerful tools.

### Applications of C#
- **Windows Applications:** Used to build desktop apps with frameworks like WPF and WinForms.
- **Web Applications & Services:** Powers dynamic websites, APIs and services using ASP.NET / ASP.NET Core.
- **Game Development:** Popular in Unity engine, one of the most widely used game development platforms.
- **Mobile Applications:** Supports cross-platform apps with Xamarin and .NET MAUI.
- **Cloud & Enterprise Solutions:** Widely used for scalable applications on Microsoft Azure and enterprise software.

### Basic Program in C#
```
using System;
namespace HelloFolks{   
    class HelloFolks{   
        static void Main(string[] args){
            Console.WriteLine("Hello Folks!");
            Console.ReadKey();
        }
    }
}
```
