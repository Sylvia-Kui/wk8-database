TITLE OF THE PROJECT:Clinic Booking and Management System 

DESCRIPTION: The Clinic Booking and Management System is a relational database solution developed using MySQL to streamline the operations of a healthcare clinic. This system enables efficient tracking and management of patients, doctors, medical appointments, and treatments. It models real-world relationships between entities such as patients, doctors, specialties, and appointments to ensure data integrity and operational functionality.

This system is designed for use by administrative staff and healthcare providers to schedule appointments, assign doctors, maintain treatment records, and manage specialties. It also helps avoid conflicts such as double-booking doctors and stores all essential patient data in a structured, retrievable format.

HOW IT RUNS: Database Creation:

The system is built entirely in SQL using MySQL.

A .sql script file is created containing all the CREATE TABLE statements with constraints and relationships.

Execution Steps:

Open a MySQL terminal or GUI (e.g., phpMyAdmin, MySQL Workbench).

Import or run the clinic_booking_system.sql file.

The script will create all the tables: Specialty, Doctor, Patient, Appointment, and Treatment.

Functionality After Setup:

Insert data for specialties, doctors, and patients.

Book appointments by inserting into the Appointment table (ensuring no overlapping for doctors).

Record treatments linked to appointments in the Treatment table.

Queries Can Be Run To:

List all upcoming appointments.

Find a doctor’s schedule.

Check treatments given to a patient.

Generate reports by joining relevant tables.

KEY FEATURES:  Supports one-to-many and many-to-one relationships.

Prevents duplicate appointments through unique constraints.

Uses foreign keys to maintain data consistency.

Stores treatment histories for each appointment.

Scalable and can be extended with billing, prescriptions, or user roles.

