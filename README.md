# Contact Management System

A C# Console Application for managing contacts and countries using a structured 3-Layer Architecture with SQL Server.

## Overview

This project demonstrates how to build a simple contact management system using C# and SQL Server while separating responsibilities across different application layers.

The application supports managing contacts and countries through operations such as adding, updating, deleting, searching, and checking whether records exist.

## Features

### Contact Management
- Find a contact by ID
- Add a new contact
- Update contact information
- Delete a contact
- List all contacts
- Check whether a contact exists
- Store contact information including:
  - First Name
  - Last Name
  - Email
  - Phone
  - Address
  - Date of Birth
  - Country
  - Image Path

### Country Management
- Find a country by ID
- Find a country by name
- Add a new country
- Update country information
- Delete a country
- List all countries
- Check whether a country exists by ID or name

## Architecture

The project follows a **3-Layer Architecture**:

```text
Presentation Layer
        ↓
Business Logic Layer
        ↓
Data Access Layer
        ↓
SQL Server Database
