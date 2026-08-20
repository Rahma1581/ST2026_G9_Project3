# ST2026_G9_Project3
Hospital Management System (HMS)An object-oriented C++ application that simulates real-world hospital workflows and clinical administration. The system manages patient care, doctor schedules, room inventories, and emergency triage by leveraging C++ Standard Template Library (STL) data structures. 
Key Features Patient Management & Medical History: Registers patients, tracks admission/discharge status, and logs medical histories in a LIFO stack for audit trails. 
Doctor Appointment Scheduling: Schedules patient appointments using FIFO queues and supports out-of-order cancellations.  
Dual Emergency Triage System: Features standard FIFO emergency queues alongside a max-heap priority queue that triages critical cases by severity level (1–5).
Diagnostics & Prescriptions: Manages diagnostic test pipelines with FIFO queues and records prescribed medications.
Automated Billing & Room Management: Automatically calculates running balances based on room tier (General Ward, ICU, Private, Semi-Private), diagnostic tests, and prescriptions while enforcing room capacity.
