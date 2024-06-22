# Hospital Management System (backend)

## Features and Functionality

- ### Patient Profile Management:
    - The system allows the management of patient profiles, including their personal information, medical history, and current treatment plan.
- ### Doctor Profile Management:
    - The system allows the management of doctor profiles, including their personal information, qualifications, and specialities.
- ### Appointment Scheduling:
    - The system allows the scheduling and rescheduling of appointments, with automated notifications to both patients and doctors.
- ### Billing and Payment Management:
    - The system allows the management of billing and payments, with automated invoice generation and tracking of payments. 

## API Calls for the Hospital Management System

### For Patient:

```angular2html
POST /patient: Create a new patient record
GET /patient: Retrieves a list of all patients
GET /patient/:id: Retrieves a specific patient's details by their ID
PUT /patient/:id: Updates an existing patient's details by their ID
DELETE /patient/:id: Deletes a specific patient's record by their ID
```

### For Doctor:

```angular2html
POST /doctor: Create a new doctor record
GET /doctor: Retrieves a list of all doctors
GET /doctor/:id: Retrieves a specific doctor's details by their ID
PUT /doctor/:id: Updates an existing doctor's details by their ID
DELETE /doctor/:id: Deletes a specific doctor's record by their ID
```

### For Appointment:

```angular2html
POST /appointment: Create a new appointment record
GET /appointment: Retrieves a list of all appointments
GET /appointment/:id: Retrieves a specific appointment's details by its ID
PUT /appointment/:id: Updates an existing appointment's details by its ID
DELETE /appointment/:id: Deletes a specific appointment's record by its ID
```

### For Billing:

```angular2html
POST /bill: Create a new bill record
GET /bill: Retrieves a list of all bills
GET /bill/:id: Retrieves a specific bill's details by its ID
PUT /bill/:id: Updates an existing bill's details by its ID
DELETE /bill/:id: Deletes a specific bill's record by its ID
```