
## EPIC Cogito 170 Class


## Table of Contents 

####  Day 1 
1. **Introduction**
2. **Users and administrators**
3. **Analytics Catalog and Radar Dashboards**
4. **SlicerDicer Populations**

#### Day 2
5. **Data Lineage** 
6. **Workbench Reports** 
7. **Dashboard Metrics** 

#### Day 3
8. **Troubleshooting** 
9. **Security** 
10. **Cogito Build** 


 
##  Chapter 2 Introduction to Users and administrators 

##  Chapter 2 Table of Contents 
 
1. **Introduction to Users and administrators**
2. **Cogito Users and Administrators**
3. **In Class Scenario**
4. **After Class Self Study**


- Additional Resources
- Reviewing the Chapter 


 
##  Chapter 2 Introduction to Users and Administrators 

Nurses, physicians, registrars, coders, and report writers all log in to Epic for a variety of tasks. Everyone
who logs in to Epic is called a user. Users perform a variety of tasks using different parts of the Epic
system.

In this class, it will be helpful to differentiate between users who perform healthcare tasks in the system
and administrators who build content to meet users needs. For Cogito, administrative tasks include
creating dashboards and reports.

By the End of This Lesson, You Will Be Able To...
1. Log in to Hyperspace
2.  Explain the difference between a user and an administrator


 
##  Cogito Users and administrators 

### Users

**Users** log in to Epic to do their jobs. The steps that a user takes in Epic are referred to as a workflow. For
example, a clinician might open their schedule, review a patients medical history, open the patients chart,
place an order, and sign a note. Different users have different workflows.

### User Workflows
Users navigate to different activities in Hyperspace when completing their **workflows**. A scheduler can use
the Appts activity to create a new appointment, a clinician can review messages from the In Basket activity,
and a report writer can modify report settings from the Analytics Catalog activity.

### Epic Menu 

The Epic menu contains all the activities a user has access to. The Epic search (under the Epic button) or
the Assistant Bar (at the top of Hyperspace) are the most efficient ways to launch a Hyperspace activity.

 
##  Cogito Users and administrators 

### Hyperspace

**Hyperspace** is Epics front end user interface, accessed on the Hyperdrive client. 
It is what most users think of as **Epic**. 
Users log in to Hyperspace to complete their workflows and do their jobs. 
Administrators also log in to Hyperspace to test and troubleshoot build.

### Hyperspace and Epics Database

**Chronicles** is Epics database management system, often referred to as **the database.** The data that users
access in **Hyperspace** lives in **Chronicles**. When a user logs in to Hyperspace and opens a patients chart,
Hyperspace is requesting data from **Chronicles**. When a user documents information in a patients chart,
they are saving data to **Chronicles**.


##  Cogito administrators 

### Administrators 

An **administrator** in Epic can configure parts of the Epic interface for users. 
Administrators can have many responsibilities depending on which applications, or parts of the Epic software,
they are responsible for managing. 

Examples of Epic applications include EpicCare Ambulatory for outpatient workflows, Stork for
obstetric workflows, and Cogito Ergo Sum, or Cogito, for analytics tools and content.



### Hyperdrive 

Technically, **Hyperspace** is a web based application. It runs on a web server, called
Hyperspace Web. When you launch the Hyperspace icon in training, youre actually
launching a specialized web browser called **Hyperdrive**. The Hyperdrive client presents the
Hyperspace Web application to users, much like how a commercially available browser
(Chrome, Edge, Firefox, etc.) presents your favorite web sites.



## Key SQL Terms 
Here’s a concise set of definitions for the specified terms:

1. **Relational Database (RDBMS)**: A type of database management system that stores data in structured tables with predefined relationships between them, allowing for efficient data retrieval and manipulation.

2. **Primary Key**: A unique identifier for a record in a table, ensuring that each entry can be distinctly identified. It cannot contain NULL values and must contain unique values.

3. **Foreign Key**: A field (or collection of fields) in one table that uniquely identifies a row in another table, establishing a relationship between the two tables. It can contain NULL values and may not be unique.

4. **Structured Query Language (SQL)**: A standardized programming language used for managing and manipulating relational databases, including querying, updating, and managing data.

5. **NULL Values**: A special marker used in databases to indicate that a data value does not exist in the database. NULL is not the same as zero or an empty string; it represents the absence of a value.

6. **SQL Data Types**: Categories that specify the kind of data that can be stored in a database column, including types such as INTEGER, VARCHAR, DATE, and BOOLEAN.

7. **SELECT Clause**: The SQL statement component that specifies which columns of data to retrieve from a database table.

8. **FROM Clause**: The SQL statement component that specifies the table or tables from which to retrieve data.

9. **WHERE Clause**: The SQL statement component that specifies conditions to filter records returned by a query, allowing only those that meet the specified criteria.

10. **GROUP BY Clause**: The SQL statement component that aggregates rows that have the same values in specified columns into summary rows, often used with aggregate functions like COUNT, SUM, or AVG.

11. **ORDER BY Clause**: The SQL statement component that specifies the order in which the result set of a query should be returned, based on one or more columns.

12. **HAVING Clause**: The SQL statement component that filters groups created by the `GROUP BY` clause based on specified conditions, often used with aggregate functions. 

These definitions provide a foundational understanding of key concepts in relational databases and SQL.


## Key Terms for cogito fundamentals 

Here are ten key terms related to Epic Cogito fundamentals, along with brief descriptions:

1. **Workbench Reports**: Customizable reports that allow users to filter, sort, and analyze data from Epics electronic health records.

2. **SlicerDicer**: A self-service data exploration tool that enables users to create ad-hoc reports and visualizations by slicing and dicing data sets.

3. **Clarity**: Epics relational database designed for detailed reporting, storing data extracted from the Chronicles database for large-scale analysis.

4. **Caboodle**: Epics enterprise data warehouse (EDW) that consolidates data from multiple sources, including Clarity, to provide a comprehensive view for analytics.

5. **Chronicles**: Epics primary non relational database where real time clinical and operational data is stored; used for day-to-day patient care activities.

6. **Data Model**: The structure that defines how data is stored and related within Epic, including entities like patients, encounters, and procedures.

7. **Metric Based Components**: Dashboard elements that display performance metrics over time, helping users track and assess key performance indicators (KPIs).

8. **Cogito**: The umbrella term for Epics analytics and reporting suite, which includes tools like Clarity, Caboodle, SlicerDicer, and Workbench Reports.

9. **Dashboards**: Visual displays in Epic that aggregate data from various sources, providing users with insights and quick access to key metrics and information.

10. **ETL (Extract, Transform, Load)**: The process used to extract data from Chronicles, transform it for analysis, and load it into Clarity and Caboodle for reporting purposes.

11. **Users**: The steps that a user takes in Epic are referred to as a workflow. For example, a clinician might open their schedule, review a patient’s medical history, open the patient’s chart,
place an order, and sign a note. Different users have different workflows. Nurses, physicians, registrars, coders, and report writers all log in to Epic for a variety of tasks. Everyone
who logs in to Epic is called a user. Users perform a variety of tasks using different parts of the Epic
system.

12. **User Workflows**: Users navigate to different activities in Hyperspace when completing their workflows. A scheduler can use the Appts activity to create a new appointment, a clinician can review messages from the In Basket activity, and a report writer can modify report settings from the Analytics Catalog activity.

13. **Administrators**: Administrators who build content to meet users  needs.



## Hyperspace Overview 


Epic Hyperspace is the user interface of the Epic Systems electronic health record (EHR) software. It serves as the primary platform through which healthcare providers access and manage patient information, perform clinical tasks, and document care. Epic is one of the most widely used EHR systems in the United States, particularly in hospitals, large healthcare organizations, and clinics.

Key features of Epic Hyperspace include:

1. **Patient Records Management**: Allows clinicians to view, update, and manage patient medical records, including history, medications, allergies, lab results, and more.

2. **Scheduling and Appointments**: Helps in scheduling patient appointments, managing calendars, and coordinating care across different departments.

3. **Clinical Decision Support**: Provides alerts, reminders, and recommendations based on clinical guidelines to help healthcare professionals make informed decisions.

4. **Order Entry**: Enables providers to order tests, medications, and procedures electronically, which improves accuracy and reduces paperwork.

5. **Billing and Revenue Cycle Management**: Integrates clinical tasks with billing processes, streamlining the workflow from patient registration to payment.

6. **Customizable Dashboards**: Users can customize their view to prioritize tasks and information relevant to their role, whether they are doctors, nurses, or administrative staff.

7. **Integration with Other Systems**: Epic Hyperspace can connect with other hospital systems (e.g., lab, radiology, pharmacy) to provide a unified platform for healthcare delivery.

The design aims to be user friendly, though it can be complex due to the wide range of functions it covers. Each role within a healthcare facility, from doctors to receptionists, may have a different version of Hyperspace tailored to their needs.



## Hyperspace Tabs

The main tabs on Epic Hyperspace typically include:

1. **Patient Lists**: Displays lists of patients assigned to the user, allowing easy access to their medical records and information.
2. **Chart Review**: Provides a comprehensive view of a patients medical history, including past visits, lab results, and notes.
3. **Visit Navigator**: Guides users through the documentation and order entry process during a patient visit.
4. **Order Entry**: Allows clinicians to place orders for medications, tests, and procedures.
5. **In Basket**: Functions as a messaging and task management tool, where users receive notifications, alerts, and messages.
6. **Schedule**: Displays and manages patient appointments, staff schedules, and room bookings.
7. **Care Everywhere**: Enables viewing and sharing of patient information across different healthcare systems using Epic. 

These tabs are often tailored to specific user roles, so not every user will see all of them.

