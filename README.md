# 🛒 E-Commerce Voucher Validation

A simple flowchart project that demonstrates how an e-commerce system validates voucher eligibility and calculates discounts based on several predefined conditions.

This project was created for **Praktikum 1** as an introduction to basic programming logic, including variables, input/output, Boolean values, conditional statements, and arithmetic operations.

## 📌 About the Project

The program simulates a voucher validation system for an e-commerce transaction.

Before a voucher can be applied, the system checks several requirements related to the transaction and customer account. If all requirements are fulfilled, the system calculates the discount and displays the final payment amount.

The voucher provides a **15% discount** with a maximum discount of **Rp50,000**.

## 🎟️ Voucher Requirements

To successfully use the voucher, the transaction must meet all of the following conditions:

- Minimum purchase of **Rp150,000**
- Account age of at least **30 days**
- Product must belong to the **Electronics** category
- The transaction must **not use another promotion**

If one of these requirements is not fulfilled, the voucher will be rejected and the customer will pay the original transaction amount.

## 💰 Discount Calculation

When all voucher requirements are satisfied, the discount is calculated as:

**Discount = Total Purchase × 15%**

The maximum discount is limited to **Rp50,000**.

The final payment is then calculated as:

**Total Payment = Total Purchase − Discount**

### Example

If the total purchase is **Rp200,000**:

- Discount = 15% × Rp200,000
- Discount = Rp30,000
- Total Payment = Rp170,000

If the calculated discount exceeds Rp50,000, the system will automatically limit the discount to **Rp50,000**.

## 🧩 Variables

| Variable | Data Type | Description |
| --- | --- | --- |
| `TotalBelanja` | Integer | Total transaction value before discount |
| `Kategori` | Boolean | Indicates whether the product is in the Electronics category |
| `UmurAkun` | Integer | Customer account age in days |
| `PromoLain` | Boolean | Indicates whether another promotion is being used |
| `Diskon` | Real | Discount calculated by the system |
| `TotalBayar` | Real | Final transaction value after discount |

## 🧠 Concepts Implemented

This project applies several fundamental programming concepts:

- Variable declaration
- Integer, Real, and Boolean data types
- User input and program output
- Conditional statements
- Nested conditions
- Arithmetic operations
- Voucher eligibility validation
- Discount calculation

## 📊 Flowchart

The flowchart below represents the complete voucher validation and discount calculation process.

![E-Commerce Voucher Validation Flowchart](./AISYAH%20THALITA%20SHAQIRAH%20FLOWCHART%20PRAKTIKUM%201%20-%20Main.png)

## 🎯 Purpose

The purpose of this project is to understand how a real-world business rule can be translated into structured programming logic.

Through this project, voucher requirements that are normally written as rules can be converted into a sequence of decisions that a computer can process automatically. It also demonstrates how multiple conditions can work together to determine whether a transaction is eligible for a discount.

## 👩‍💻 Author

**Aisyah Thalita Shaqirah**  
Sistem Informasi  
Fakultas Ilmu Komputer  
Universitas Brawijaya

---

**Praktikum 1 — E-Commerce Voucher Validation & Discount Calculation**
