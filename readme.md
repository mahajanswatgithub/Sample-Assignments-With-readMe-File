### Frameworks and language used 
* SpringBoot Framework 
* java 

### Data Flow
* Controller - RestController
 
  Used with @GetMapping, @PostMapping,@DeleteMapping, @RequestBody,@PathVaraiable,@Validated,@RequestParam,@Valid and @Autowired which is linked with business logic in service class.

* Services

  1. UserService

     i. SignUp User

     ii. SignIn User

     iii. SigOut User

     iv. Create Insta Post

     v. Remove Insta Post

     vi. Add Comment

     vii. Authorize Comment Remover

     viii. Remove Insta Comment

     ix. Add Like

     x. Get Like Count By Post

     xi. Authorize Like Remover

     xii. Remove Insta Like

     xiii. Follow User

     xiv. Authorize Unfollow
    
     xv. UnFollow User

  2. PostService

     i. Create Insta Post

     ii. Remove Insta Post

     iii. Validate Post

     iv. Get Post By Id


  3. LikeService

     i. Add Like

     ii. Is Like Allowed On This Post

     iii. Get Like Count For Post

     iv. Find Like

     v. Remove Like

  4. FollowService

     i. Start Following

     ii. Is Follow Allowed

     iii. Find Follow

     iv. Unfollow

  5. CommentService

     i. Add Comment

     ii. Find Comment

     iii. Remove Comment

  6. AuthenticationService

     i. Authenticate

     ii. Save AuthToken

     iii. Find First By User

     iv. Remove Token

     
* Repository

  JpaRepository

### DataBase Design
![ER-InstaApp-DFD](ER-InstaApp.png)

### Data Structure used in your project

* Arraylist

### Database used in your project
 
* MYSQL-database

### Project Summary

* This is "Instagram Backend" Application which follows MVC-architecture.I have created this project by using spring initilizer by taking 7 dependency i.e., lombok, spring web, Mysql, JPA, Email, swagger,and Validation. In my model package I have User, Authentication, Like,Follow, Post, Comment class which has all its related data.
* We can signUp and signIn Instagram App.
* We can comment, Like and Follow User
* We can also Remove comment and unfollow the user.
* Posting of post is also possible by this application.

