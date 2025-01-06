 <h1>Online Auction System (PL/SQL Project)</h1>

<h2> Project Description</h2>

The Online Auction System is a PL/SQL-based project designed to manage auctions in a database environment. It includes functionalities for:

Managing users (buyers and sellers)

Managing items listed for auction

Allowing buyers to place bids

Determining the winner of an auction

Automatically closing auctions and storing winner information

This project is implemented using Oracle PL/SQL and consists of:

Database tables for users, items, auctions, bids, and winners

Stored procedures to handle auction operations

Functions to retrieve auction details

Triggers to enforce constraints

<h2>Features</h2>

User Management:

Add buyers and sellers to the system.

Distinction between buyers and sellers based on user roles.

Item Management:

Sellers can list items for auction.

Items have details such as name, description, base price, and auction duration.

Auction Management:

Auctions are created for items listed by sellers.

Auctions have statuses like ongoing and closed.

Bid Management:

Buyers can place bids on ongoing auctions.

Ensures that bid amounts are higher than the current highest bid.

Winner Determination:

When an auction closes, the highest bidder is recorded as the winner.

Data Retrieval:

Retrieve auction details, including the highest bid and status, using PL/SQL functions.

<h2>Database Structure</h2>

Tables

Users:

Stores user details (ID, name, email, role).

Items:

Stores item details listed for auction.

Auctions:

Tracks auction status and the highest bid.

Bids:

Stores bid details placed by buyers.

Winners:

Records the winner of each closed auction.

Sequences

Used to generate unique IDs for users, items, auctions, bids, and winners.

<h2>Installation Instructions</h2>

Prerequisites

Oracle Database installed and configured

Oracle SQL Developer or any SQL client tool

Steps to Set Up the Project

Clone the Repository

git clone https://github.com/<your-username>/Online-Auction-Project.git

Run the SQL Script

Open the online_auction_project.sql file in Oracle SQL Developer.

Execute the script to create tables, sequences, procedures, triggers, and functions.

Insert Sample Data

Populate the tables with sample data using the provided SQL insert statements.

Test the Functionality

Call the procedures (e.g., Add_Bid, Close_Auction) and verify the output.

Retrieve auction details using the Get_Auction_Details function.

<h2>Contributing</h2>

If you would like to contribute to this project:

Fork the repository.

Create a new branch for your feature/bug fix.

Submit a pull request.

<h2>License</h2>

This project is licensed under the MIT License. Feel free to use and modify it as needed.
