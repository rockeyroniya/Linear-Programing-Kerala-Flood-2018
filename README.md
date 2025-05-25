# Linear-Programing-Kerala-Flood-2018
Project Overview
This project models a disaster relief logistics problem using linear programming. The goal is to minimize the total transportation cost while ensuring relief supply demands are met at different camps, under resource constraints like vehicle capacity and availability.

The model is based on a real-world inspired scenario from the Kerala Floods of 2018, originally explored in a seminar. It implements optimization logic in Python using the PuLP library and outputs results to a formatted Excel file.

Key Features
Linear programming model to optimize transportation logistics.

Incorporates multiple constraints: vehicle capacity, supply limits, demand satisfaction, and trip limits.

Outputs detailed, merged, and summarized results in Excel.

Includes cost breakdowns and total metrics.

Technologies Used

Python 3

PuLP: Linear programming solver.

pandas: Data manipulation.

openpyxl: Excel file handling and formatting.

JSON: Parsing structured transport data.

Files Needed

camp.csv — Contains demand per relief camp and distances between stations and camps.

station.csv — Defines storage capacity and available transport modes at supply stations.

vechicle.csv — Lists vehicle types, capacities, and transportation cost per kilometer.
