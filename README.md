Features Implemented
✅ Basic Authentication (HTTP Basic)
✅ SecurityFilterChain configuration
✅ Role-based Authorization using @PreAuthorize
✅ Password Encryption using BCryptPasswordEncoder
✅ InMemoryUserDetailsManager (for testing)
✅ JdbcUserDetailsManager (for database-based authentication)
✅ H2 Database Integration
✅ Stateless Session Configuration


## 🔗 API Endpoints

| Endpoint   | Access                     |
|------------|----------------------------|
| `/public`  | Public (No Authentication) |
| `/user`    | USER role required         |
| `/admin`   | ADMIN role required        |


Security Concepts Covered

1. SecurityFilterChain
   Central configuration for securing HTTP requests
   Defines which endpoints require authentication

2. Authentication
   Handled using Spring Security
   Users defined via InMemory or JDBC

3. Authorization
   Role-based access using @PreAuthorize

4. Password Encoding
   Passwords encrypted using BCryptPasswordEncoder

5. UserDetailsService
   Manages user data (in-memory or database)


Tech Stack Spring Boot
Spring Security
H2 Database
JDBC
BCryptPasswordEncoder
InMemoryUserDetailsManager
JdbcUserDetailsManager


Author
Harshil Patel