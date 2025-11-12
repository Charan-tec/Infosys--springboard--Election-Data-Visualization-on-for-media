ElectViz Election Data Visualization for Media

Project Overview

ElectViz is an interactive, multi-page Power BI dashboard created for the Infosys Springboard Virtual Internship (Batch 6.0). This project transforms decades of complex Indian state election data (1977-2014) into a clear, intuitive, and powerful analytical tool.

It is designed for media organizations, political analysts, and the public to explore voting patterns, party performance, and historical trends without needing to sift through complex spreadsheets.


Project Objective

The primary goal of this project is to analyze and visualize complex Indian state election data.

Key objectives include:

Consolidating key election metrics, including total votes, party participation, seats won, and voter turnout.

Identifying historical voting trends by visualizing data across different election years.

Providing a comparative analysis of political party performance at both the state and national levels.

Creating a granular breakdown of seat distribution by state and constituency.

Empowering users with interactive slicers and filters to find specific, dynamic insights.

Technical Stack

Microsoft Power BI Desktop: The primary tool used for data modeling, analysis, and creating all visualizations.

Power Query Editor: Used extensively for data cleaning, transformation, and preparing the raw data for analysis.

DAX (Data Analysis Expressions): Used to create all key measures and KPIs, such as Total Votes, Total Parties, Voter Turnout %, etc.

Microsoft Excel: Used as the initial data source for the raw election data.

The Data Challenge: Cleaning & Modeling

A significant challenge was the complexity of the raw data. The dataset spanned decades and included:

3044 Million+ Total Votes

1637 Unique Political Party entries

A major part of the project involved using Power Query Editor to clean and standardize the 1,637 party names, handling duplicates, and formatting the data for accurate analysis.

ElectViz Dashboard Showcase

The final report consists of 5 interactive pages:

Indian State Election Analysis (Main Dashboard)
This is the main landing page, providing a high-level overview of the entire dataset. It features key slicers that control the entire report.

<img width="1123" height="768" alt="Screenshot 2025-11-12 231236" src="https://github.com/user-attachments/assets/259f806c-ad70-4887-a0cc-4247c64479e7" />

Key KPIs: Total Votes (3044M), Total Parties (1637), Total Seats (5670), Voter Turnout % (5.52%).

Key Visuals: Seats Won by Party Name, Sum of Seats Won by State.

Interactivity: Slicers for Election Year, Political Party, State, and Constituency Type.

Temporal & Turnout Analysis
This page focuses on historical trends and voter engagement.

<img width="1028" height="682" alt="Screenshot 2025-10-22 143755" src="https://github.com/user-attachments/assets/c046c306-e9e8-4067-9b53-9938ef00d5e9" />


Key Visuals:

Total Votes by year (Line Chart)

Voter Turnout % by State Name (Donut Chart)

Top Performers & Cumulative Growth
This dashboard gives a quick snapshot of the most significant entities and their historical growth.

<img width="1087" height="711" alt="Screenshot 2025-10-22 143820" src="https://github.com/user-attachments/assets/47db1fe5-7088-494f-8e9f-11eb169f07f1" />

Key Visuals:

Top Party: Independent (Card)

Top State: Uttar Pradesh (Card)

Count of Seats Won by year (Waterfall Chart)

Share & Distribution Analysis
This page breaks down performance by state and party vote share.

<img width="1051" height="701" alt="Screenshot 2025-10-23 220047" src="https://github.com/user-attachments/assets/5d11c24c-b44f-46a5-8ef2-378e3b19da8d" />

Key Visuals:

Count of Seats Won by State name (Funnel Chart)

Vote share by party (Pie Chart)

State-wise Party Seat Distribution
This is the most granular dashboard, providing a detailed matrix for specific analysis.

<img width="1078" height="710" alt="Screenshot 2025-10-22 143915" src="https://github.com/user-attachments/assets/1670b971-fbba-47c9-9b8c-9835080549f8" />

Key Visual: A detailed Matrix with State Name as rows, Party Abbreviation as columns, and Sum of Seats as the values.

How to View

Clone this repository.

Download the Electviz Election Data Visualization.pbix file.

Open the file using Microsoft Power BI Desktop

Aknowledgement : 

This internship helped me enhance my analytical and visualization skills through practical exposure to real-world data. I am deeply thankful to Infosys Springboard for the valuable learning resources, guidance, and support provided throughout the internship

Developed by :

               CHARAN
