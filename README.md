# Music-Database
This project is a PostgreSQL-based music store database system that supports administrative and customer-facing functionalities. It simulates a digital music store where administrators can manage tracks and customers can browse, select, and purchase music. The system includes comprehensive SQL queries to analyze music trends, sales distribution, and customer behavior.
It is designed for educational purposes and demonstrates practical applications of relational databases, SQL querying, and simple UI integration using Python and Microsoft Visual Studio.

#Features
~ Browse available music tracks by genre, artist, or album.
~ Users can select tracks and simulate a purchase, adding to invoice lines.
~ Admin can insert new tracks and manage the database using a UI.
~ Generate business insights:
  - Top-spending customers by country.
  - Most popular genres and artists.
  - Sales distribution by state and quarter.
  - Revenue tracking and purchase trends.

#Tech Stack
Database: PostgreSQL
Backend: Python (Microsoft Visual Studio using psycopg)

~ Tools Used:
 - pgAdmin / DBeaver for database management
 - Microsoft Visual Studio for interactive backend operations

~ Libraries:
 - psycopg2 (PostgreSQL connector)

#Database Schema
The database schema includes:
 - customers: Customer info
 - invoices: Purchase invoices
 - invoice_items: Individual track purchases
 - tracks: Music tracks
 - albums, artists, genres: Metadata tables
 - employees: Admin and support staff
 - media_types: Track file formats
