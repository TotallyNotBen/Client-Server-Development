# Client-Server-Development

1. How do you write programs that are maintainable, readable, and adaptable?

I write maintainable, readable, and adaptable programs by organizing code into reusable parts, using clear names, adding helpful comments, and keeping each section focused on one job. In Project One, the CRUD Python module made the database code reusable because the create, read, update, and delete operations were separated from the dashboard itself. This made Project Two easier because the dashboard widgets could call the CRUD module instead of repeating database connection code. The main advantage was that changes to the database logic only needed to be made in one place. In the future, this CRUD module could be reused for other dashboards, reports, or applications that need to connect to MongoDB.

2. How do you approach a problem as a computer scientist?

I approach problems by first understanding the client’s requirements, then breaking the work into smaller tasks. For the Grazioso Salvare dashboard, I had to think about what data the client needed, how it should be filtered, and how users would interact with it visually. This project was different from some previous assignments because it connected multiple pieces together: a database, a Python module, and an interactive dashboard. In the future, I would use the same strategy of identifying the client’s goals, designing the database structure around those goals, testing queries carefully, and building reusable code that can support future changes.

3. What do computer scientists do, and why does it matter?

Computer scientists solve problems by designing systems, writing programs, managing data, and creating tools that help people work more efficiently. This matters because good software can turn large amounts of data into useful information. For a company like Grazioso Salvare, the dashboard helps users quickly search animal shelter data, filter animals based on rescue needs, and view location information on a map. This kind of project can save time, reduce manual work, and help the company make better decisions when selecting animals for training and rescue operations.
