# Hospital-Management-System
A Java-based Hospital Management System that applies OOP principles (inheritance, interfaces, abstraction). It manages doctors, patients, departments, and hospital services. Supports bill calculation, doctor salary sorting, and patient billing with emergency and long-term cases.
Project Description

This Java project implements a simplified Hospital Management System that models real-world hospital entities and operations.
The system demonstrates Object-Oriented Programming (OOP) concepts such as inheritance, abstraction, interfaces, polymorphism, and encapsulation.

🔹 Key Features:

Doctor Management

Each doctor has an ID, name, specialty, degree, base salary, and overtime details.

Salary is calculated based on degree and overtime hours.

Doctors can be sorted by salary using the Comparable interface.

Patient Management

Abstract class PatientBase defines common patient attributes (ID, name, age, medical history, department).

Two patient types are supported:

EmergencyPatient: adds an emergency fee + taxed hospital services.

LongTermPatient: calculates cost based on days admitted + taxed hospital services.

Patients can be sorted by their total bill.

Department Management

Each department holds lists of patients and doctors.

Supports adding doctors and patients while preventing duplicates.

Hospital Services & Billing

Services (e.g., X-Ray, MRI, Lab Tests) are linked to patients.

Bills are generated with a tax rate (Billable interface).

The system calculates the total hospital bill for all patients.

Driver Class

Demonstrates system functionality:

Creating departments, doctors, patients, and services.

Sorting patients and doctors.

Generating individual and total bills.

⚡ Technologies & Concepts Used:

Java OOP principles (inheritance, interfaces, abstract classes)

Collections (ArrayList, Collections.sort)

Encapsulation with getters/setters

Polymorphism (calculateBill() overridden in patient types)

📖 Use Case:
This project serves as a learning example for applying Java OOP concepts in a practical scenario (hospital system), making it useful for students and beginners to understand class relationships and interface implementation.
