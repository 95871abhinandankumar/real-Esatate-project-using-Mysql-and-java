# real-Esatate-project-using-Mysql-and-java
CS241 - Project Description
1 INSTRUCTIONS
(1) Read the entire description before you begin your work.
(2) The specifications given are from end-users, so they may not be precise and complete. State all your assump￾tions in your deliverables.
2 PROJECT DESCRIPTION
A DBMS needs to be implemented for a real estate office, that sells houses and apartments within a city. The office
needs to store a lot of data, specifically:
• agents: An agent is responsible for interacting with buyers and sellers, to show properties to them and facilitate
sales or giving on rent.
• details of homes/apartments: The address, selling price, rent, details of the house (example: size: 1500 sq. ft,
number of bedrooms: 2)
3 DATA GENERATION
You can see magicbricks.com, 99acres.com, makaan.com etc. for good examples of data.
4 PROJECT REQUIREMENTS
(1) E-R Model
(a) Construct an E-R diagram representing the conceptual design of the database.
(b) Be sure to identify primary keys, relationship cardinalities, etc.
(2) Relational Model
(a) After creating an initial relational design from your E-R design, refine it based on the principles of relational
design.
(b) Create the relations in MySQL.
(c) Create indices (indices will be taught later) and constraints as appropriate.
(d) If, as you refine your design, you discover flaws in the E-R design, go back and change it (even if the earlier
design passed the checkpoint.) Your final E-R design must be consistent with your relational design.
(3) Populate Relations
(a) Include enough data to make answers to your queries interesting and nontrivial for test purposes.
(4) Queries: Run enough queries to ensure that your database is populated the way you intended it to be. Given
below are the queries that you must demonstrate. You may be asked to demonstrate additional queries.
(a) Find addresses of homes in your city (for example Guwahati) with rent between Rs.20,000 and Rs. 40,000 per
month.
(b) Find details of homes for rent in G.S.Road (you can use the name of another locality if your city is different)
with at least 2 bedrooms and costing less than Rs.10,000 per month. Show the contact number(s) of agents
who can show you these properties.
. 1
2
(c) Find the name of the agent who has sold the most property in the year 2021 by total amount in rupees.
(d) Find the addresses of homes in your city that are available for sale and that has at least 2 bed rooms. List the
asking price and the number of bedrooms, with other details that may be necessary.
(e) List the details of the most expensive houses and the houses with the highest rent, in the database.
(5) Interfaces: There are two types of users who access the database. Each may need a different interface:
(a) The database administrator (you) may use SQL via the command line.
(b) The real estage agent’s office, to get 1) sales reports for each agent, consisting of the sale dates, property details
and selling price and 2) how many properties have been given on rent by each agent for what amount, in
which area, when.
(c) Agents, to update the database when a property is rented or sold.
These interfaces can be built as 1) Web applications using Java applets or a scripting language. 2) A standalone
Java application using Swing to create a GUI 3) A standalone Java application with a command line interface 4)
Any other GUI tool you may know
(6) Concurrency: The database must support more than one agent accessing the database at a time along with
someone from the real estate office. Make sure that the required guarantees are provided.
