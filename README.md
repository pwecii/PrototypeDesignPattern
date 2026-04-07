# 🧬 Prototype Design Pattern – Problem Scenario

## 📌 Problem Overview

In a system where different types of animals (such as Sheep, Cow, and Horse) need to be created frequently, object creation can become inefficient and repetitive. Each animal has multiple attributes (e.g., number of legs, sound, food, name, color), and initializing these values every time a new object is needed can lead to:

* Redundant code
* Increased complexity
* Higher resource consumption

Additionally, some objects may require slight variations (e.g., different names for Sheep), but most of their properties remain the same. Creating these objects from scratch each time is not optimal.

---

## 💡 Proposed Solution

To address this issue, we use the **Prototype Design Pattern**.

Instead of creating new objects directly, we:

1. Create a **prototype instance** of each animal.
2. Store these prototypes in a centralized registry.
3. Clone the prototype whenever a new object is needed.
4. Modify only the necessary attributes (e.g., name).


## Uml Diagram

<img width="797" height="467" alt="image" src="https://github.com/user-attachments/assets/fe566887-96e2-4a3c-9424-257a2afbfab4" />
