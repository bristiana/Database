# 🎵 Festival Management Database System

A comprehensive relational database system designed for managing music festivals and events, developed as part of my Database course at University of Bucharest.

## 📋 Project Overview

This database system manages all aspects of music festival organization including:
- **Events & Venues**: Festival scheduling and location management
- **Artists & Performances**: Artist assignments to stages and song catalogs
- **Ticket Sales**: Participant registration and service tiers
- **Staff Management**: Organizers, managers, and sponsors with role hierarchies
- **Equipment Tracking**: Technical equipment allocation per stage

## 🏗️ Database Architecture

### Entity-Relationship Design
- **16 interconnected tables** with complex relationships
- **Inheritance hierarchy**: Staff → Organizer/Manager/Sponsor
- **Normalized to 3NF** to eliminate data redundancy
- **Advanced constraints** ensuring data integrity

### Key Entities
- `EVENIMENT` - Festival events and scheduling
- `ARTIST` - Performer information and stage assignments  
- `PARTICIPANT` - Attendee registration and demographics
- `BILET` - Ticket sales and service tiers
- `STAFF` - Personnel management with specialized roles
- `SCENA` - Stage management and capacity planning
- `ECHIPAMENT` - Technical equipment tracking

## 🔧 Technical Implementation

### Database Features
- **Oracle Database** with PL/SQL procedures
- **Complex SQL queries** with subqueries and joins
- **Data aggregation** and analytical functions
- **Transaction management** with rollback capabilities
- **Sequence generators** for primary key management

### Advanced SQL Operations
- Synchronized and unsynchronized subqueries
- Window functions and data grouping
- Complex joins across multiple tables
- Conditional logic with CASE statements
- String and date manipulation functions

## 📊 Key Statistics

- **16 normalized tables** with referential integrity
- **200+ records** across all entities
- **5+ complex analytical queries**
- **3+ update/delete operations** with subqueries
- **Full CRUD operations** implemented

## 🚀 Setup Instructions

1. **Database Setup**
   ```sql
   -- Run scripts in order:
   @sql/01-create-sequences.sql
   @sql/02-create-tables.sql
   @sql/03-insert-data.sql
