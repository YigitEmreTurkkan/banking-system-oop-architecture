# Banking System: OOP-Driven Architecture

![Screenshot_87](https://user-images.githubusercontent.com/93987661/209542094-823df1d8-befb-41ea-b2d3-81d87d2f965c.png)

## 🏦 Project Overview
This repository features a comprehensive, modular banking engine designed with core **Object-Oriented Programming (OOP)** principles. Developed as part of an **Information Systems Engineering** curriculum, the project demonstrates a professional approach to managing complex financial workflows, user roles, and transactional integrity.

The system is built to handle multiple account types, secure authentication, and real-time transaction processing, serving as a robust foundation for scalable enterprise applications.

---

## 🏗️ Architectural Design
The solution is engineered to maximize maintainability and extensibility through classical OOP concepts:

* **Encapsulation:** Domain entities manage their own states, ensuring data integrity through strictly defined access modifiers.
* **Abstraction:** Core banking services are decoupled from implementation details, allowing for flexible persistence layers.
* **Inheritance:** Specialized account models (Individual vs. Corporate) derive from a base account structure to reuse lifecycle logic while enforcing specific business rules.
* **Polymorphism:** Dynamic behavior in interest calculations and fee processing is handled through interface-based strategies.

---

## 🖼️ Platform Showreel & Modules

### 1. User Authentication & Security
The system implements a secure entry point for different user tiers, ensuring role-based access control from the start.
![Screenshot_88](https://user-images.githubusercontent.com/93987661/209542098-99d0dbc6-4fd1-4d1b-807b-a50f7bef80ac.png)
![Screenshot_89](https://user-images.githubusercontent.com/93987661/209542099-e00438e5-40bb-4093-9ce6-c97d4643d539.png)

### 2. Management Dashboard
A centralized hub for monitoring financial health, managing assets, and navigating core banking functions.
![Screenshot_90](https://user-images.githubusercontent.com/93987661/209542102-81332700-6e7a-4c2e-96e6-5729817c6cb1.png)
![Screenshot_91](https://user-images.githubusercontent.com/93987661/209542103-d77b1aa2-ceda-44fc-828e-8c06801adbaa.png)

### 3. Account Lifecycle Management
Supports a diverse range of financial products, including individual savings and corporate commercial accounts, each with unique validation logic.
![Screenshot_92](https://user-images.githubusercontent.com/93987661/209542104-fbabd755-b076-42a2-af52-5422d17ab56b.png)
![Screenshot_93](https://user-images.githubusercontent.com/93987661/209542107-825d327c-50d3-432c-bff0-388b3334471a.png)
![Screenshot_94](https://user-images.githubusercontent.com/93987661/209542108-6d98e7f0-b75c-4ef8-89dd-47a34d728573.png)

### 4. Transaction & Fund Orchestration
Handles atomic money transfers and deposit/withdrawal workflows with deterministic business rule enforcement.
![Screenshot_95](https://user-images.githubusercontent.com/93987661/209542109-5ad652f3-9e4d-434d-a99b-9cb33461b073.png)
![Screenshot_96](https://user-images.githubusercontent.com/93987661/209542115-63f2528d-8ea0-484a-b0fb-c9ea7207569e.png)
![Screenshot_97](https://user-images.githubusercontent.com/93987661/209542117-ed07ddb8-5d51-46cd-8925-02da29c376b4.png)

### 5. Auditing & Reporting
Transparent logging of all financial activities, providing a clear audit trail for compliance and user history.
![Screenshot_98](https://user-images.githubusercontent.com/93987661/209542120-bef184d1-626e-4304-b135-5c9728291712.png)
![Screenshot_99](https://user-images.githubusercontent.com/93987661/209542122-2a02fe33-78f7-4fe2-9a77-61175bd2d9ae.png)

---

## 🛠️ Tech Stack
| Component | Technology |
| :--- | :--- |
| **Backend** | C# / .NET Framework (ASP.NET WebForms) |
| **Frontend** | HTML5, CSS3, Bootstrap |
| **Patterns** | Repository Pattern, Factory Method, Singleton |
| **Architecture** | N-Tier Layered Architecture |

---

## 🚀 Cloud-Native Evolution (Roadmap)
As a **Junior Cloud Engineer**, I view this monolithic architecture as a prime candidate for modernization:
1. **Containerization:** Wrapping the .NET artifacts into Docker images for environment parity.
2. **Microservices:** Decoupling the 'Transaction Engine' and 'Identity Service' into independent, scalable units.
3. **CI/CD:** Implementing automated pipelines to deploy the banking core to Kubernetes clusters.


---
*For inquiries or technical deep-dives, please open an issue or reach out via LinkedIn.*