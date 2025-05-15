# 102. Functional vs. Non-Functional Requirements  

Understanding and analyzing requirements is crucial for a successful software or system project. These requirements are mainly divided into two types: **Functional** and **Non-Functional**. Functional requirements define **what** a system should do, while non-functional requirements define **how well** the system should perform under certain conditions.

---

## 🛠️ What are Functional Requirements?

Functional requirements specify the **core actions or behaviors** a system must perform to meet user needs.

- They represent **direct user expectations** — features that are visible in the final product.
- Typically documented in terms of inputs, operations, and expected outputs.

📌 **Examples:**
- What are the core features the system must support?
- What edge cases or scenarios should the system handle?

![image](https://github.com/user-attachments/assets/230f9002-47fa-4bc0-abdc-f03e99c64b02)

---

## 🚦 What are Non-Functional Requirements?

These define the **quality attributes** of a system — focusing on **performance, security, usability**, and other constraints.

- Known as **non-behavioral** requirements.
- Vary in priority depending on the project scope and goals.

📌 **Examples:**
- Each request should be processed with minimal latency.
- The system must be secure and reliable.

---

## ➕ What are Extended Requirements?

Extended requirements are **"nice-to-have"** features that may not be essential for system success but are beneficial if implemented.

📌 **Examples:**
- The system should track performance metrics and analytics.
- It should support service health monitoring.

---

## 💡 Examples of Functional and Non-Functional Requirements

Illustrations from real-world systems to show the contrast between the two types:

### 1. 🏦 Online Banking System

- **Functional:**
  - Users can log in using a username and password.
  - Users can view their account balance.
  - Notifications sent after transactions.

- **Non-Functional:**
  - Response time must be under 2 seconds.
  - Transactions must be encrypted and secure.
  - System should handle 100M users with low downtime.

### 2. 🍕 Food Delivery App

- **Functional:**
  - Browse menus and place orders.
  - Payment and order tracking in real time.

- **Non-Functional:**
  - Menu should load in under 1 second.
  - Support 50,000 concurrent users.
  - Intuitive interface for first-time users.

---

## 🔍 Differences between Functional and Non-Functional Requirements

| **Aspect**                    | **Functional Requirements**                              | **Non-Functional Requirements**                            |
|------------------------------|-----------------------------------------------------------|------------------------------------------------------------|
| **Definition**                | What the system should do (tasks, features).              | How the system should perform (qualities).                 |
| **Purpose**                   | Behavior and features of the system.                      | Performance, usability, and system attributes.             |
| **Scope**                     | Actions and operations.                                  | Conditions and constraints.                                |
| **Examples**                  | Login, transactions, data processing.                     | Security, latency, scalability, reliability.               |
| **Measurement**               | Easy to test via outputs.                                | Harder to quantify, often via benchmarks.                  |
| **Development Impact**        | Directly influences code and logic.                       | Impacts architecture, deployment, and performance tuning.  |
| **User Needs Focus**          | Visible and direct to users.                             | Focuses on overall experience.                             |
| **Documentation**             | Use cases, user stories, functional specs.                | Performance docs, tech specs, SLAs.                        |
| **Testing/Evaluation**        | Unit, integration testing.                               | Performance, security, usability testing.                  |
| **Dependency**                | Core to fulfilling functionality.                         | Depends on how functionality is delivered.                 |

---

## ⚖️ Importance of Balancing Both Types

Balancing both ensures a system that is not only **functional but also usable, reliable, and scalable**.

- 🚀 **Improves User Experience:** A fast, intuitive system increases satisfaction.
- 📈 **Enhances Performance:** Non-functional attributes like scalability prevent crashes under load.
- 🛡️ **Prevents Failures:** Security and reliability guard against data loss and downtime.
- 💸 **Reduces Long-Term Costs:** Avoids costly reworks due to overlooked performance issues.
- 🔄 **Supports Future Growth:** Maintainability and flexibility help in scaling and updating.

---

## ⚠️ Common Challenges in Defining Requirements

Designing both types of requirements isn’t always straightforward due to several obstacles:

- ❓ **Ambiguity:** Vague requirements lead to misinterpretations.
- 🔄 **Changing Needs:** Business and user needs evolve frequently.
- ⬆️ **Prioritization:** Hard to decide which requirements come first.
- 📏 **Measuring Non-Functional Requirements:** Often subjective and benchmark-based.
- 🔁 **Conflicts/Overlaps:** Security vs. speed, or complexity vs. usability.

---

## 📋 How to Gather Functional and Non-Functional Requirements

Different approaches are used to gather each type effectively:

### 🔧 Functional Requirements:
- **Interviews:** Direct conversations with users or stakeholders.
- **Surveys:** Collect feedback from larger audiences.
- **Workshops:** Brainstorming sessions with diverse teams.

### ⚙️ Non-Functional Requirements:
- **Benchmarks:** Use industry standards to set performance goals.
- **Security Audits:** Define compliance requirements early.
- **Usability Testing:** Observe how real users interact with prototypes.

---
