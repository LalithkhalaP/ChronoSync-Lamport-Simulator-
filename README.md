# ChronoSync-Lamport-Simulator-

# Lamport Logical Clock Simulator

## 📌 Project Overview

The **Lamport Logical Clock Simulator** is a mini project designed to demonstrate how logical clocks work in distributed systems. It helps users understand the ordering of events across multiple processes using Lamport's logical clock algorithm.

The simulator updates logical timestamps when events occur and when messages are sent or received between processes.

## 🎯 Objectives

- Understand logical clocks in distributed systems.
- Demonstrate event ordering across multiple processes.
- Simulate message communication between processes.
- Visualize how Lamport timestamps are updated.

## ✨ Features

- Professional and user-friendly interface.
- Multiple process simulation.
- Event generation and timestamp updates.
- Message sending and receiving simulation.
- Visual representation of logical clock values.
- Simple and interactive demonstration.

## 🛠️ Technologies Used

- HTML
- CSS
- JavaScript

## ⚙️ Lamport Clock Algorithm

The Lamport Logical Clock follows these rules:

1. Each process maintains a logical clock.
2. Before every event, the process increments its clock by 1.
3. When a process sends a message, it attaches its current timestamp.
4. When a process receives a message, it updates its clock using:

   `Clock = max(Local Clock, Received Timestamp) + 1`

These rules help maintain the correct logical ordering of events in a distributed system.

## 📚 Applications

- Distributed systems education.
- Understanding event ordering.
- Studying message communication between processes.
- Learning logical clock synchronization concepts.

## 📄 License

This project is developed for educational and academic purposes.

