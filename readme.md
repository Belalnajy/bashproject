# Bash Database Management System

A Zenity-based GUI database management tool for executing CRUD operations on databases and tables via a user-friendly interface.

![CLI Database Management](https://img.shields.io/badge/CLI-Database%20Management-blue)
![Zenity GUI](https://img.shields.io/badge/GUI-Zenity%20Dialogs-green)

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)

## Features

### Database Operations
- 🗃️ Create new databases
- 📄 List existing databases
- 🔌 Connect to databases
- 🗑️ Delete databases

### Table Operations (Within Connected Database)
- 📊 Create tables with columns
- 🗂️ List existing tables
- 🗑️ Drop tables
- ➕ Insert data into tables
- 🔍 Select/Query data from tables
- 🚮 Delete records from tables
- ✏️ Update table records

## Requirements
- `bash` (v4.0 or newer)
- `zenity` (for GUI dialogs)
- Linux-based OS (Tested on Ubuntu/Debian)

## Installation

1. **Clone repository**
```bash
git clone https://github.com/Belalnajy/bashproject.git
```
2. **Install dependencies**
```bash
sudo apt-get install zenity
```
3. **Make script executable**
```bash
chmod +x DBMS
```

## Usage

**Start the application:**
```bash
./DBMS
```