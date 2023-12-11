# Hi!

This is an exercise project.

## Features

- ##### Registration
- ##### Login
- ##### Upload of files that represent the energy consumption per year split by month and based on a 3 zone time frame (F1,F2,F3).
- ##### Table view of uploaded data and management
- ##### Data visualization of stacked consumption
- ##### Simulation of bill cost

The stack will be structured as following: MySQL, PHP, Angular 17.

## MySQL

Enforced actually as I have a hosting on aruba which is based on MySQL. I'd rather use PostgreSQL

## PHP

Just vanilla, no framework, at least the expectation is to go straight with this approach

## Angular 17

Will be used with PrimeNG for components, tailwind for layout management and Chart JS for some simple data visualization


# Features breakdown

## Registration

Requires 3 data from the user: e-mail, username, password.

## Login

Requires 2 data from the user: username, password.

## Upload file

One given file with CSV format, each data column will have 4 rows.

First row will be skipped as it is the header, not a value row.

Rows from 2nd to 4th will be value rows, corresponding to zones of day time frame: F1, F2, F3.

## Table view

A simple data table which allows the user to see uploaded data to the server and delete them.

# Data visualization

Chart displaying data from the previous year ( with year by year form )

# Simulation of bill cost

TBD.
