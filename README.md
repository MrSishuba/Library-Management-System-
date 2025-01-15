# Library Management System  

The **Library Management System** is a web-based application built using the **ASP.NET MVC** framework and **Entity Framework** for database interaction. This application allows users to effectively manage students and books within the library, as well as generate actionable reports on borrowing trends.  

## Features  

### 1. **Home Module**  
- **Welcome Page**: Provides an overview of the Library Management System.  
- **Student and Book Management**:  
  - Add, edit, view, and delete student and book records.  
  - View student and book details in an organized manner.  

### 2. **Maintenance Module**  
- **Author, Type, and Borrow Management**:  
  - CRUD operations for authors, book types, and borrow records.  
  - Maintain a detailed catalog of library resources and borrow history.  

### 3. **Reporting Module**  
- **Actionable Insights on Borrowing Trends**:  
  - Generate reports highlighting the **most borrowed books** in the library.  
  - Use **bar charts** and **pie charts** to visually represent borrowing patterns.  
  - Analyze borrowing data to understand student preferences and optimize the library's collection.  

#### Reporting Charts  
- **Bar Chart**: Displays borrow counts for top borrowed books, highlighting their popularity.  
- **Pie Chart**: Shows the proportional contribution of each book's borrow count relative to the total.  

### 4. **Save and Export Reports**  
- Reports can be saved as PDF files with proper pagination for easy sharing and archival.  
- Built using **Newtonsoft.Json** for data handling and formatting.  

## Purpose  
The primary objective of this project is to demonstrate:  
- Seamless integration between the **MVC design pattern** and **Entity Framework**.  
- The ability to implement robust **CRUD operations**.  
- Practical use of data-driven insights to enhance library management.  

## Technical Stack  
- **Backend**: ASP.NET MVC, Entity Framework  
- **Frontend**: HTML, CSS, JavaScript, Bootstrap  
- **Database**: SQL Server  
- **Charting**: Libraries for bar and pie chart visualization  
- **PDF Export**: Newtonsoft.Json  

## Installation and Setup  
1. Clone the repository:  
   ```bash
   git clone https://github.com/YourUsername/LibraryManagementSystem.git
   --Change Machine name in Web.Config file for connection string
