# Introduction
As 

## Choice of classes
Since i started my education at linnéUniversity i have always though through class diagrams, so before i started to think on a high level with issues and user storys i start with what kind of classes might be relevant for the module.
After i build my classes i think about the conceptual classes.

## Classes for class diagram, first thoughts

### Person
An abstact class to build patient and doctor classes, if needed later it can be expanded with nurses and more but for this simplifycation patient and doctor will be enough.

### Patient
The primary actor for the module. The person that is going to reserve times.

### Doctor
Is set to an appointment with a patient.

### Hospital
The main structure holder. Contains the rooms, hires the doctors. It is also the holder of the BookingSystem(wich could within a bigger app could be more standalone if more hospitals would be connected).

### Room
The main holder of the appointments.

### Appointment
A placeholder for an exam. Contains infomation of who is the patient, doctor, which room, the tima and date for the exam.

### Booking system
The compounder of an appointment, gets a request from the patient and sets up an Appointment.

## Choice of conceptual classes - domain model