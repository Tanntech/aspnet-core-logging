# ASP.NET Core Logging – Concept & Demos

This repository contains multiple projects created to **understand and implement logging in ASP.NET Core MVC and WebAPI applications**.  
All projects were made by me independently to **learn the core concepts of logging and its practical implementation**.

---

## 🔹 What is Logging & Why It’s Important

**Logging** is the process of recording application events, errors, or important information for debugging, monitoring, and auditing.  
It is a **cross-cutting concern**, meaning it applies across multiple layers of an application (controllers, views, services) without polluting business logic.

**Why logging is important:**
- Helps track application execution flow
- Makes debugging and error tracking easier
- Maintains historical records for auditing
- Improves maintainability and scalability
- Teaches clean architecture concepts (separating concerns)

---

## 🔹 What I Have Done

In this repository, I created **self-contained demo projects** to explore logging in different ways:

1. **MVC Action Filter Logger**  
   - Implemented a custom `FileLogger` using Singleton pattern.  
   - Created `IETFilter` action filter to log request lifecycle automatically.  
   - Logged controller actions and view rendering without adding log statements inside controller code.  

2. **MVC Middleware Logger (future/extension)**  
   - Demonstrates global logging for all HTTP requests.  
   - Middleware logs request start and end events.  

3. **MVC Logger with Views (future/extension)**  
   - Demonstrates logging interactions with ViewData and view lifecycle.  

4. **WebAPI Logger (future/extension)**  
   - Demonstrates logging API requests and responses using custom FileLogger and filters.

> Each project is **modular**, and I built them from scratch to understand how logging can be applied in real-world scenarios.

---

## 🔹 Folder Structure (Example for First Project)

