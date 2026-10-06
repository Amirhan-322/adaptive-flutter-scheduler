# Adaptive Task Scheduling for Flutter

This project explores a self-adaptive scheduling system for CPU-intensive tasks in Flutter applications. The scheduler will dynamically choose between execution in the main isolate, a short-lived isolate, and a persistent worker based on task characteristics, execution history, and current UI performance.

The project includes a prototype Flutter library, reproducible benchmark workloads, and an experimental evaluation comparing adaptive scheduling with fixed execution strategies across different devices and platforms.