# 🐍 Python Object-Oriented Programming (OOP)

![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

## Overview
This repository serves as a comprehensive guide and code collection for understanding Object-Oriented Programming (OOP) in Python. It contains practical examples, scripts, and explanations of core OOP concepts designed to help developers write clean, modular, and scalable code.

## Table of Contents

| 📌 Section | 📖 Sub-topics / Details |
| :--- | :--- |
| **[The Foundation](#the-foundation-classes-and-objects)** | • [Classes and Objects](#classes-and-objects) |
| **[The Four Pillars of OOP](#the-four-pillars-of-oop)** | • [1. Encapsulation](#1-encapsulation)<br>• [2. Inheritance](#2-inheritance)<br>• [3. Polymorphism](#3-polymorphism)<br>• [4. Abstraction](#4-abstraction) |
| **[Repository Structure](#repository-structure)** | Overview of the folder layout and script organization |
| **[Getting Started](#getting-started)** | Prerequisites and repository installation steps |
| **[Usage](#usage)** | Command-line execution examples |
| **[Contributing](#contributing)** | Guidelines for submitting issues and pull requests |
| **[License](#license)** | MIT License information |

---

## The Foundation: Classes and Objects

Before diving into the pillars, it is essential to understand the basics. A **Class** is a blueprint for creating objects. An **Object** is an instance of a class. The `__init__` method is the constructor used to initialize the object's attributes.

```python
class Car:
    def __init__(self, brand, model):
        self.brand = brand
        self.model = model

    def display_info(self):
        print(f"Car: {self.brand} {self.model}")

# Creating an object
my_car = Car("Toyota", "Corolla")
my_car.display_info()
