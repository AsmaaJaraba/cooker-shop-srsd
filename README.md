<div align="center">

# 🍳 Cooker Shop — Software Requirements Specification & Design

### A complete UML software engineering case study
**COMP433 — Software Engineering · Birzeit University**

[![Course](https://img.shields.io/badge/Course-COMP433-1d4e74)](#)
[![University](https://img.shields.io/badge/Birzeit-University-c9622b)](#)
[![UML](https://img.shields.io/badge/Modelling-UML-1e7a52)](#)
[![Status](https://img.shields.io/badge/Project-Complete-1e7a52)](#)

</div>

---

## 📖 Overview

This repository contains the full software engineering lifecycle for the **Cooker Shop** system — a physical cooker retail store modelled as an online e-commerce platform. The project applies software engineering techniques across four phases — requirement elicitation, analysis, modelling, and system design — producing a complete **UML model** and a final **Software Requirements Specification & Design (SRSD)** document.

The Cooker Shop sells gas, electric, induction, and hybrid cookers to households, restaurants, and businesses, offering delivery, installation, and after-sales maintenance. The system models online browsing, ordering, payment, scheduling, and maintenance workflows.

---

## 🗂️ Repository Structure

| Folder | Contents |
|---|---|
| **`01-Phase1-Business-Definition/`** | Business definition of the Cooker Shop — submission + instructor feedback. |
| **`02-Phase2-Requirements/`** | User & system requirements and effort/cost estimation — submission + feedback. |
| **`03-Phase3-Analysis-Modelling/`** | Actors, use-case diagram, use-case specifications, activity diagram — submission + feedback. |
| **`04-Final-Report/`** | The final SRSD report, the final project presentation, and final feedback. |
| **`diagrams/`** | Exported UML diagrams — use case, analysis class, detailed class, and sequence. |

> Each phase folder holds both the **submission** and the **instructor feedback** for that phase, kept together as a record of the project's iterative, feedback-driven improvement. Phase 4 (system design) work is consolidated into the **final report** and the **diagrams** folder.

---

## 📐 UML Diagrams

The `diagrams/` folder contains the project's final UML models:

| Diagram | File |
|---|---|
| **Use-Case Diagram** | `use-case-diagram.png` |
| **Analysis Class Diagram** (first-cut) | `analysis-class-diagram.png` |
| **Detailed Class Diagram** | `detailed-class-diagram.png` |
| **Sequence Diagram** (Place Order) | `place-order-sequence-diagram.png` |

The use-case diagram defines the system's actors — **Customer** and **Administrator** (principal), and **PaymentGateway**, **EmailSystem**, **DeliveryPersonnel**, and **Technician** (secondary) — with verb-first use cases and `«include»` / `«extend»` relationships.

---

## 🔧 What the System Does

The Cooker Shop Website System supports:

- **Browsing & discovery** — browse, search, and compare cooker products
- **Shopping** — manage a cart, place and pay for orders online
- **Order management** — track order status, cancel orders
- **Fulfilment** — schedule delivery and installation of purchased cookers
- **After-sales** — submit maintenance requests for products under warranty
- **Administration** — manage products, update stock, and process orders

It integrates with two external systems: a **payment gateway** (card processing) and an **email service** (confirmations).

---

## 🏗️ Process Model

The project followed an **incremental, feedback-driven process**: each phase was built, submitted, reviewed against instructor feedback, and refined in the next iteration — mirroring the incremental software process model studied in the course. The feedback kept alongside each phase documents this learning loop.

---

## 👥 Team — Group 7

| Member | University ID |
|---|---|
| Asmaa Jaraba *(Project Manager)* | 1231081 |
| Misk Mashahreh | 1231150 |
| Masa Awad | 1220290 |
| Anwar Atawna | 1222275 |
| Abdel Rahman Sabbagh | 1203015 |

**Course:** COMP433 Software Engineering · **Instructor:** Dr. Adel Taweel · **Institution:** Birzeit University

---

<div align="center">
<sub>Built as an academic software engineering case study · Birzeit University · 2026</sub>
</div>
