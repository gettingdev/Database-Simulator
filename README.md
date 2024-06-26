# Python CLI Database Simulator

Welcome to the Python CLI Database Simulator! This project was created as part of my journey in learning Python. Please note that this project is purely educational and is not intended for real-world use. It is located in the "C:\dev" directory.

## Introduction

This Python CLI Database Simulator is a command-line tool that simulates basic database functionalities such as creating databases, tables, and managing their contents. it allows you to perform CRUD (Create, Read, Update, Delete) operations on the simulated data.

## Requirements

- Python 3.x
- Windows operating system (due to the hardcoded path to `"C:\dev"`)

## How to Use

1. Clone this repository to your local machine. `git clone https://github.com/gettingdev/Database-Simulator`
2. Navigate to the project directory in your command-line interface.
3. Run the main Python script using the command: `python main.py` or `py main.py`
4. Follow the on-screen instructions to interact with the CLI Database Simulator.
5. Experiment with creating databases, tables, and adding/deleting data to improve your understanding of database concepts and enhance your algorithmic and logical skills.

## Usage
1. Creating a new database `create database [database_name]`
2. Show databases `show databases database_name`
3. use database `use [database_name]`
4. create head `create head [head1, head2, head3, ...]`
5. Adding data to table `add [data1, data2, data3, ...`
6. Viewing all data in head/table `see all`
7. Update line `update line [head_name: new_data]` or you can update many tables in one row `update line [head1_name: new_data1, head2_name_ new_data2, head3_name: new_data3]`
8. adding data before line `add before line [number] [data1, data2, data3]`
9. adding data after line `add after line [number] [data1, data2, data3]`
10. viewing data with restrictions `see but limit [number]`
11. View data starting from a specific order `see but starting from [number]`

   

## Disclaimer

This project is purely educational and serves as a learning exercise. It does not provide real database functionality and should not be used in production environments. The hardcoded path to "C:\dev" restricts its functionality to Windows systems and may not work on other operating systems.

