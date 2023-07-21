### Frameworks and language used 
* SpringBoot Framework 
* java 

### Data Flow
* Controller - RestController
 
  Used with @GetMapping, @PostMapping,@DeleteMapping, @RequestBody,@PathVaraiable,@Validated,@Valid and @Autowired which is linked with business logic in service class.

* Services

  1. AppointmentService

     i. Get All Appointments

     ii. Save Appointment

     iii. Get Appointment For Patient

     iv. Cancel Appointment

  2. DoctorService

     i. Add Doctor

     ii. Get All Doctors

     iii. PatientService

     iv. SignUp Patient

     v. Get All Patients

     vi. SignIn Patient

     vii. Schedule Appointment

     viii. Cancel Appointment

     ix. SigOut Patient

* Repository

  JpaRepository

### DataBase Design
![ER-DoctorApp-DFD](ER-DoctorApp.png)

### Data Structure used in your project

* Arraylist

### Database used in your project
 
* MYSQL-database

### Project Summary

* This is "Doctor-App" Application which follows MVC-architecture.I have created this project by using spring initilizer by taking 7 dependency i.e., lombok, spring web, Mysql, JPA, Email, swagger, and Validation. In my model package I have Doctor,Patient and Appointment class which has all its related data.
* We can signUp and signIn app.
* Book appointment or Cancel Appointment.
* Get all patient Data.
* Add or get All doctors.

