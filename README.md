# 🍽️ Smart Canteen Management System

A Python-based **Smart Canteen Management System** designed to simplify food menu management, customer ordering, billing, and inventory tracking.

This project was developed as part of the **Introduction to Python** course to demonstrate practical use of Python programming concepts such as functions, modules, conditional statements, loops, exception handling, SQLite database operations, CRUD operations, and modular programming.

---

## 📌 Project Overview

Managing a college canteen manually can become difficult when there are many food items, customers, orders, and stock records.

The **Smart Canteen Management System** provides a simple computerized solution for managing the major activities of a canteen.

The system allows users to:

- Manage food items
- View and search the menu
- Add new food items
- Update food information
- Place customer orders
- Calculate bills automatically
- Maintain order history
- Manage inventory
- Add and update stock
- Detect low-stock items
- Store information using SQLite

The project is developed as a **console-based Python application** with a modular structure.

---

## 🎯 Objectives

The main objectives of this project are:

1. To develop a simple and user-friendly canteen management system using Python.
2. To automate food ordering and billing.
3. To maintain accurate food inventory records.
4. To reduce manual work in managing canteen operations.
5. To demonstrate Python programming concepts in a real-world application.
6. To store and retrieve data using an SQLite database.
7. To implement input validation and error handling.
8. To create a modular and maintainable Python project.

---

## 🚨 Problem Statement

In a traditional canteen, food menus, orders, bills, and inventory may be managed manually.

This can lead to problems such as:

- Difficulty maintaining stock records
- Errors in calculating bills
- Difficulty tracking previous orders
- Lack of automatic low-stock notifications
- Time-consuming manual data entry
- Difficulty searching for food items
- Increased chances of human error

The proposed system addresses these problems by providing a centralized Python-based application for managing canteen operations.

---

## 👥 Target Users

The system can be used by:

- College canteen staff
- Canteen administrators
- Food counter staff
- Students and customers
- Small food service businesses

---

## ⭐ Features

### 🍔 1. Menu Management

The menu management module allows the user to:

- View available food items
- Add new food items
- Search for food items
- Update food information
- Remove food items
- Manage food categories
- View food prices
- View available stock

### 🛒 2. Order & Billing Management

The order module allows the user to:

- Place new orders
- Select multiple food items
- Enter required quantities
- Check item availability
- Calculate item-wise subtotal
- Calculate total order amount
- Automatically calculate 5% tax
- Generate a bill
- Store order history
- View previous order details

### 📦 3. Inventory Management

The inventory module allows the user to:

- View current stock
- Add stock
- Update stock
- Automatically reduce stock after an order
- Detect low-stock items
- Generate a low-stock report
- Automatically make an item unavailable when stock reaches zero

---

## 🔄 System Workflow

```text
                    ┌───────────────────────┐
                    │         START         │
                    └───────────┬───────────┘
                                │
                                ↓
                    ┌───────────────────────┐
                    │   Initialize Database │
                    └───────────┬───────────┘
                                │
                                ↓
                    ┌───────────────────────┐
                    │     Main Menu         │
                    └───────────┬───────────┘
                                │
             ┌──────────────────┼──────────────────┐
             ↓                  ↓                  ↓
      ┌─────────────┐    ┌─────────────┐    ┌──────────────┐
      │    Menu     │    │   Orders &  │    │  Inventory   │
      │ Management  │    │   Billing   │    │ Management   │
      └──────┬──────┘    └──────┬──────┘    └──────┬───────┘
             │                  │                  │
             └──────────────────┼──────────────────┘
                                ↓
                       ┌─────────────────┐
                       │ SQLite Database │
                       └────────┬────────┘
                                │
                                ↓
                       ┌─────────────────┐
                       │      EXIT       │
                       └─────────────────┘
