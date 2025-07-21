# 🚗 Smart Car Parking System using LinkedList

A smart car parking lot management application built using **C**, focusing on **linked list-based data structures** without the use of arrays. This project simulates real-world parking management by handling vehicle registration, space allocation, membership handling, and payment processing.

---

## 🔧 Features

- Register new or returning vehicles with full owner details
- Allocate parking space based on **membership level**
- Calculate total parking hours and charges
- Manage **gold**, **premium**, and **non-member** benefits
- Update and upgrade membership levels
- Maintain and update parking space status (free/occupied)
- Sort and view:
  - Vehicles by number of parkings
  - Vehicles by total payment
  - Parking spaces by frequency of use
  - Parking spaces by revenue generated
- File handling for initial data loading
- **No arrays used**; implemented entirely using **Linked Lists**, **Stacks**, and **Queues**

---

## 🧠 Project Summary

This project allows users to register vehicles entering a parking lot, manage membership levels, assign parking slots intelligently, calculate parking fees, and maintain space status. Built using linked list structures for dynamic memory management and real-world simulation of parking data.

---

## 📌 Allocation Policy

- **Gold Members** → Parking spaces **1–10**  
- **Premium Members** → Parking spaces **11–20**  
- **Non-Members** → Allocated first free space from **21–50**

---

## 🎖 Membership Policy

- **No Membership**: < 100 hours  
- **Premium**: ≥ 100 hours  
- **Gold**: ≥ 200 hours  

---

## 💰 Payment Policy

- ₹100 for first 3 hours  
- ₹50 per extra hour  
- 10% discount for members (Gold or Premium)

---

## 🧪 Tools & Technologies Used

- C (Implementation)
- File Handling
- Linked Lists (Singly, Doubly, Circular)
- Stack & Queue (ADT)
- Command-Line Interface (CLI)

---

## 📂 Sample Data

- At least **10 parking entries** preloaded via file handling (includes gold, premium, and non-member users)

---


