# OSProject-Thread-Synchronization-
Project on Thread Sychronization(Ticket Booking System)

# 🎫 Ticket Booking System

A multithreaded ticket booking simulation written in **C**, demonstrating the use of **POSIX threads (pthreads)** and **semaphores** for synchronized access to shared resources. This project is aimed at showcasing effective concurrency control in a real-time simulation.


## 📌 Objective

To simulate a ticket booking environment where multiple users attempt to book seats concurrently. The system ensures thread-safe operations using semaphores to prevent race conditions and maintain data integrity.


## 🛠️ Tech Stack

- **Language:** C
- **Multithreading:** POSIX Threads (`pthread.h`)
- **Synchronization:** Semaphores (`semaphore.h`)
- **Platform:** Linux/Unix (Ubuntu recommended)

## 🧠 Concepts Covered

- Thread creation and joining
- Semaphore-based critical section management
- Dynamic memory allocation
- Real-time seat allocation with validation
- Prevention of double booking


## 🔄 How It Works

1. **Input Gathering:**
   - Grid size (rows × columns)
   - Number of users

2. **User Thread Execution:**
   - Each user (thread) is prompted to book seats.
   - Synchronization ensures only one user accesses seat selection at a time.

3. **Seat Booking:**
   - Seat availability is checked before confirmation.
   - Booked seats are marked and stored securely.

4. **Output:**
   - Final seat layout is displayed post all bookings.
   - Resources are deallocated and semaphores are destroyed.



