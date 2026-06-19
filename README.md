# Client-Server-Development


## CS 340 Portfolio Reflection

### How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by organizing the code into smaller parts that each have a clear job. In this project, the CRUD Python module helped make the program easier to manage because the database logic was separated from the dashboard code. Instead of writing MongoDB connection and query code directly inside the dashboard, I used the `AnimalShelter` class to handle database operations.

This made the dashboard easier to read because the Dash code could focus on the user interface, filters, table, chart, and map. It also made the project more adaptable because the CRUD module could be reused or updated without rewriting the entire dashboard. For example, if the database changed or new queries were needed, I could update the CRUD module instead of changing every dashboard component.

In the future, this CRUD Python module could be reused for other animal shelter dashboards, database applications, or client projects that need to read, create, update, or delete MongoDB records. It could also be expanded with more methods to support additional reports, searches, or data management tools.

### How do you approach a problem as a computer scientist?

I approach a problem as a computer scientist by first understanding what the client needs, then breaking the problem into smaller tasks. For the Grazioso Salvare project, I looked at the dashboard requirements and identified the main features that needed to work: connecting to MongoDB, displaying animal shelter data, filtering rescue candidates, updating a chart, and showing animal locations on a map.

My approach to this project was different from some earlier assignments because this project felt more like building a complete application for a real client. Instead of only writing one program that solves one small problem, I had to think about how the database, Python code, dashboard layout, and user interaction all worked together.

In the future, I would use a similar approach for other database projects. I would start by reviewing the client’s goals, studying the data, identifying the important fields, and creating queries that match the client’s needs. I would also test each part of the system one step at a time so that database issues, display problems, or filtering errors could be fixed early.

### What do computer scientists do, and why does it matter?

Computer scientists design and build software systems that solve real problems. They work with data, create programs, test solutions, and improve how people use technology. This matters because good software can help organizations make faster and better decisions.

For a company like Grazioso Salvare, this dashboard could help make their work more efficient by allowing them to quickly search through animal shelter data and identify dogs that may be good candidates for rescue training. Instead of manually looking through large amounts of data, the dashboard allows the user to filter records by rescue type, view important animal details, see breed information, and locate animals on a map.

This type of project shows how computer science can turn raw data into a useful tool. By making the data easier to search and understand, the dashboard can help the organization save time, reduce mistakes, and focus more on selecting and training rescue animals.
