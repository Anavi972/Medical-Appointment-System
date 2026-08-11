# Medical Appointment System

The developed system retains the structure of a common deployment scenario which includes backend and frontend systems. The user interacts with the front-end interface like website, which communicates with an REST API. The client has the ability to interact directly with the REST API.

## Scope


Only a section of the system was implemented as specified in assignment discussion. The chosen section is specified below:
- Login or Register
- Update Client Details (including Medical Record)
- Check Appointment Time-slot Availability
- Book an Appointment
- View and Update Appointment (including Notes)

Some changes needed to be made to facilitate the partly implemented system, which included no room or practitioner allocation, or any treatment or payment resolve. Core to the partly implemented system is appointment booking which includes client login and registration, availability check, etc.

## Implementation

Routes are REST API endpoints the users can visit. Each route is configured in controllers which act like services. Each service access the JPA data repository which holds model instances, e.g. Client.java which holds fields like ID, name, etc.

<p align="center">
  <img height="300" src="https://user-images.githubusercontent.com/26774196/152198443-b1be9908-1aca-46f1-89e9-99771d3c7869.png">
</p>






