# TicketMaster Java Application

## Description
This Java application simulates a simplified version of TicketMaster, allowing users to manage and interact with show data. The program reads show information from a file, stores it in a list, and provides various functionalities such as sorting shows by performer or price, searching for shows by city, and displaying show details.

The application features a text-based menu system for the user to sort and search shows. It uses basic file handling, sorting algorithms (Selection Sort and Insertion Sort), and search functionality to create an interactive experience for managing ticketing information.

## Features
- **Read Show Data from File:** Load show information from a text file (`shows.txt`).
- **Search by City:** Find and display shows that match a specific city.
- **Sort by Performer (A-Z or Z-A):** Sort the list of shows alphabetically by performer.
- **Sort by Price (Low-High or High-Low):** Sort shows by price in ascending or descending order.
- **Display Show Details:** Displays detailed information about each show in a formatted list.

## File Format for Show Data
The show data file (`shows.txt`) should contain information about shows in the following format:

How to Run:

Clone the repository
Open the project in your preferred IDE (e.g., IntelliJ, Eclipse).
Make sure the shows.txt file is placed in the root directory of the project, or adjust the file path accordingly.
Run the TicketMasterDriver class.

Shows.txt:

01-10-25 120.50 50 Tyler the Creator, Los Angeles  
02-15-25 85.75 40 Kendrick Lamar, New York  
03-20-25 99.99 35 Drake, Chicago  
04-05-25 110.00 25 Billie Eilish, Miami  
05-10-25 150.25 20 Beyoncé, Houston  
06-15-25 95.50 30 Harry Styles, London  
07-20-25 140.75 45 The Weeknd, Toronto  
08-25-25 125.00 50 Travis Scott, Atlanta  
09-05-25 80.50 60 Doja Cat, Las Vegas  
10-10-25 175.25 20 Rihanna, Paris  
11-15-25 105.75 55 Post Malone, Seattle  
12-20-25 135.00 25 Frank Ocean, San Francisco  
01-10-25 95.25 40 Bad Bunny, Mexico City  
02-15-26 115.00 30 SZA, Washington D.C.  
03-20-26 90.50 45 Lil Nas X, Orlando  
04-05-26 130.00 35 J. Cole, Denver  
05-10-26 85.75 50 Megan Thee Stallion, Dallas  
06-15-26 150.50 20 Dua Lipa, Berlin  
07-20-26 110.00 40 Ed Sheeran, Sydney  
08-25-26 120.75 25 BTS, Tokyo  
09-05-26 80.00 60 Imagine Dragons, Rio de Janeiro  
10-10-26 145.25 30 Khalid, Cape Town  
11-15-26 100.50 50 Alicia Keys, Amsterdam  
12-20-26 125.00 35 Justin Bieber, Shanghai  
01-10-26 175.00 20 Adele, Dubai 
02-20-25 140.00 30 Taylor Swift, Chicago
02-25-25 135.00 40 Bruno Mars, New York
03-15-25 120.75 50 Olivia Rodrigo, Sydney
03-25-25 100.50 35 Sam Smith, Los Angeles
04-10-25 145.00 25 Blackpink, Miami
05-20-25 125.50 40 Coldplay, New York
06-05-25 95.75 50 H.E.R., Chicago
06-25-25 110.00 30 John Legend, Atlanta
07-15-25 105.25 35 Shawn Mendes, Toronto
07-30-25 80.00 60 Paramore, London
07-31-25 75.79 12 The Weeknd, Chicago


