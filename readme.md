### Frameworks and language used 
* SpringBoot Framework 
* java 

### Data Flow
* Controller - Rest Controller
 
  Used with @GetMapping, @PutMapping, @RequestBody, @RequestParam, @PathVariable, @DeleteMapping and @AutoWired and linked with the business logic in the Service Class

* Services

1. Add a perticular Room
2. Update Room Type through roomId
3. Get the list of rooms or find a particular Room by roomId
4. Delete a perticular Room using roomId
5. We can Able to find Room by roomPrice using custom Finder

* Repository

  CrudRepository

### Data Structure used in your project

* Arraylist

### Database used in your project
 
* h2-database

### Project Summary

* This is "Hotel-Management" Application which follows MVC-architecture.I have created this project by using spring initilizer by taking 5 dependency i.e., lombok, spring web,H2,JPA and Validation. In my model package I have HotelRoom class which has all hotel related data.
* A Room type can be updated through its roomId
* We can Able to fetch all the list of Rooms
* We can delete a perticular Room using roomId

