# Event Management System  

## Overview  
The **Event Management System** is a dynamic web application designed for seamless event booking and management. The project integrates JSP for the front end,
Servlets for request processing, and MySQL for database operations. It features an admin dashboard with advanced functionalities and a customer interface for easy bookings.  

---

## Features  

### Customer Features  
- Book events by selecting categories.  
- View booked events and their statuses.  
- Provide reviews and ratings for events.  
- Download booking confirmation as a PDF.  
- Reset password using the "Forgot Password" functionality.  

### Admin Features   
- Manage user accounts and delete inquiries.  
- Add, update, or delete events dynamically.  
- View and respond to customer inquiries.  
- Confirm or reject event bookings.  

---

## File Structure  

### **Controller Package**  
Handles the flow of requests and responses between the front end and back end. Key files include:  
- `DeleteEnquiry.java`: Handles the deletion of customer inquiries.  
- `DeleteUser.java`: Manages user deletion.  

### **Model Package**  
Contains all entity classes representing the database structure. Key files include:  
- `Customer.java`: Represents customer details.  
- `ProductEnquiry.java`: Handles product inquiries.  
- `ListEnquiry.java`: Manages a list of customer inquiries.  
- `Events.java`: Represents event details.  
- `Ratings.java`: Stores user ratings and reviews.  
- `User.java`: Represents the user entity.  

### **Web Files (JSP)**  
Located in the `web` directory, these files manage the front-end interface:  
- **General**:  
  - `header.jsp`, `footer.jsp`, `index.jsp`  
  - `login.jsp`, `login_header.jsp`, `forgot_password.jsp`  
- **Admin-Specific**:  
  - `admin_header.jsp`, `add_event.jsp`, `delete_event.jsp`  
  - `enquiry_list.jsp`, `manage_users.jsp`  
- **Customer-Specific**:  
  - `event_booking.jsp`, `event_category.jsp`, `view_event.jsp`  
  - `view_review.jsp`, `review_client.jsp`  
- **PDF Management**:  
  - `pdf.jsp`: Generates booking confirmation in PDF format.  

---

## Technologies Used  
- **Backend**: Java (JSP, Servlets)  
- **Frontend**: HTML, CSS, Bootstrap, JavaScript  
- **Database**: MySQL  
- **PDF Generation**: Java Libraries  
- **IDE**: Eclipse  

---

## Setup and Installation  

### Prerequisites  
1. **Java JDK**: Version 8 or later.  
2. **Eclipse IDE**: For development.  
3. **MySQL Server**: For database operations.  
4. **Tomcat Server**: To deploy the application.  
