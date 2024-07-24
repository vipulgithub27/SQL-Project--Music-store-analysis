# SQL Project - Music Store Data Analysis

Welcome to the SQL Music Store Data Analysis project! This repository contains a comprehensive analysis of a digital music store's data, providing valuable business insights through a series of carefully constructed SQL queries. The project is organized into three sets of questions, ranging from easy to advanced, demonstrating different levels of SQL proficiency and practical applications.

![Digital music store](https://github.com/user-attachments/assets/479d35c6-18c0-46d4-a6fd-4008c538f4da)


## Table of Contents

- [Introduction](#introduction)
- [User Story](#user-story)
- [Project Structure](#project-structure)
- [Schema](#schema)
- [Question Sets](#question-sets)
  - [Question Set 1 - Easy](#question-set-1---easy)
  - [Question Set 2 - Moderate](#question-set-2---moderate)
  - [Question Set 3 - Advanced](#question-set-3---advanced)
- [Technologies Used](#technologies-used)


## Introduction

The primary goal of this project is to analyze the sales data of a digital music store to uncover meaningful business insights. The analysis is performed using SQL queries, which are organized into different difficulty levels to showcase a progression in SQL skills. This project is a demonstration of SQL skills for data analysis, providing clear examples of practical SQL applications in a business context.

## User Story

### Background

Our digital music store has been thriving, with a wide variety of music tracks available for purchase. However, to further enhance our business strategy, we need to delve deeper into our sales data. This project was initiated to extract actionable insights from our database to drive marketing, sales, and customer engagement strategies.

### The Analyst's Journey

As a data analyst working for the digital music store, I am exploring sales data to answer some key business questions. The business requirement is to understand the customer base better, identify top-performing products, and determine strategic opportunities for growth. My role is to use SQL to analyze the data and present findings that can influence decision-making at the highest level.

## Project Structure

The project is divided into three main sections:

1. **Question Set 1 - Easy:** Fundamental queries focusing on basic SQL operations and data retrieval.
2. **Question Set 2 - Moderate:** Intermediate queries involving more complex conditions and ordering.
3. **Question Set 3 - Advanced:** Advanced queries that require multi-table joins, aggregations, and nested queries.

## Schema- Music Store Database

To provide context for the SQL queries, here is the schema of the tables used in this project:

![MusicDatabaseSchema](https://github.com/user-attachments/assets/001a0458-9049-4b05-81e4-48fca720c161)


## Question Sets

### Question Set 1 - Easy

1. **Who is the senior most employee based on job title?**
   - Identify the most senior employee to understand the leadership structure.
2. **Which countries have the most invoices?**
   - Determine the geographical distribution of sales.
3. **What are the top 3 values of total invoices?**
   - Identify the highest sales transactions.
4. **Which city has the best customers?**
   - Determine the city with the highest total invoice sums to target for a promotional music festival.
5. **Who is the best customer?**
   - Identify the customer who has spent the most money to understand high-value customer profiles.

### Question Set 2 - Moderate

1. **Rock Music Listeners:**
   - Return the email, first name, last name, and genre of all rock music listeners, ordered alphabetically by email.
2. **Top Rock Bands:**
   - Return the artist name and total track count of the top 10 rock bands.
3. **Longest Tracks:**
   - Return all track names that are longer than the average song length, ordered by length.

### Question Set 3 - Advanced

1. **Customer Spending on Artists:**
   - Return customer name, artist name, and total spent by each customer on each artist to understand customer preferences.
2. **Most Popular Genre by Country:**
   - Return each country with its top genre based on the highest amount of purchases to tailor marketing strategies.
3. **Top Customer by Country:**
   - Determine the customer who has spent the most on music in each country to identify top customers and potentially reward them.

## Technologies Used

- **PostgreSQL:** Database management system used for storing and querying data.
- **PgAdmin4:** Database management tool for interacting with PostgreSQL.


