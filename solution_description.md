
## Table of Contents 

- Day 1 
1. **Introduction**
2. **Users and administrators**
3. **Analytics Catalog and Radar Dashboards**
4. **SlicerDicer Populations**
- Day 2
5. **Data Lineage** 
6. **Workbench Reports** 
7. **Dashboard Metrics** 
- Day 3
8. **Troubleshooting** 
9. **Security** 
10. **Cogito Build** 

- Appendix A: Complete your training track 
- Appendix B: Cogito Fundamentals Certifiaction Project 
- Appendix C: Additional Practics 
- Appendix D: Reviews



## Introduction 
## FAQ’s about EPIC Training

1. **Where can I ask questions about the self-study?**
   - Our email queue cogitotrainingsubmissions@epic.com is always monitored and we’d be happy to assist!
   - You can also attend study halls and Cogito Trainer Office Hours if you’d like to get more “at the elbow” support from a trainer. Email our queue for more information.


2. **How long does it take?**
   - If you are new to SQL, set aside 10-12 hours to complete the self-study.


3. **How do I get started?**
   - You will need a UserWeb account. Once that is set up, use this link: [RPT101i SQL I Self-Study](#).
   - You may use our online system to practice.
   - Request access using this link: [Certification Environment Registration](https://training.epic.com/CertEnvRegistration), then head here: [Epic Access](https://access.epic.com/).
   - Search for “Study SQL Studio”.
   - The username and password are both ‘train’.


4. **How long is the assessment?**
   - There is no time limit, and you can start/stop the assessment at any time and come back to it.
   - You can attempt the assessment multiple times! There is a daily limit of 2 submissions.
   - In total, plan for roughly 1-2 hours of testing.


5. **Do I need to attend any classes before completing the self-study?**
   - No, you may complete the self-study at any time.

If you cannot complete the RPT101i SQL I Self-Study before attending CDW110v, please attend a later session of the class and subsequent classes. Review the list of future CDW110v offerings on the Course Catalog and reach out to registrations@epic.com with your preference.

Please email CogitoTrainingSubmissions@epic.com if you have any questions or concerns.


 
##  Chapter 2 - Introduction to Users and administrators 

##  Chapter 2 - Table of Contents 
 
1. **Introduction to Users and administrators**
2. **Cogito Users and Administrators**
3. **In Class Scenario**
4. **After Class Self Study**


- Additional Resources
- Reviewing the Chapter 


 
##  Chapter 2 - Introduction to Users and Administrators 

Nurses, physicians, registrars, coders, and report writers all log in to Epic for a variety of tasks. Everyone
who logs in to Epic is called a user. Users perform a variety of tasks using different parts of the Epic
system.

In this class, it will be helpful to differentiate between users who perform healthcare tasks in the system
and administrators who build content to meet users’ needs. For Cogito, administrative tasks include
creating dashboards and reports.

By the End of This Lesson, You Will Be Able To...
- Log in to Hyperspace
- Explain the difference between a user and an administrator


 
##  Cogito Users and administrators 

### Users

**Users** log in to Epic to do their jobs. The steps that a user takes in Epic are referred to as a workflow. For
example, a clinician might open their schedule, review a patient’s medical history, open the patient’s chart,
place an order, and sign a note. Different users have different workflows.

### User Workflows
Users navigate to different activities in Hyperspace when completing their **workflows**. A scheduler can use
the Appts activity to create a new appointment, a clinician can review messages from the In Basket activity,
and a report writer can modify report settings from the Analytics Catalog activity.

### Epic Menu 

The Epic menu contains all the activities a user has access to. The Epic search ﴾under the Epic button﴿ or
the Assistant Bar ﴾at the top of Hyperspace﴿ are the most efficient ways to launch a Hyperspace activity.

### Hyperspace

**Hyperspace** is Epic’s front‐user interface, accessed on the Hyperdrive client. 
It’s what most users think of as “Epic”. 
Users log in to Hyperspace to complete their workflows and do their jobs. 
Administrators also log in to Hyperspace to test and troubleshoot build.

### Hyperspace and Epic’s Database

**Chronicles** is Epic’s database management system, often referred to as “the database.” The data that users
access in **Hyperspace** lives in **Chronicles**. When a user logs in to Hyperspace and opens a patient’s chart,
Hyperspace is requesting data from **Chronicles**. When a user documents information in a patient’s chart,
they are saving data to **Chronicles**.

 
##  Cogito administrators 

### Administrators 

An **administrator** in Epic can configure parts of the Epic interface for users. 
Administrators can have many responsibilities depending on which applications, or parts of the Epic software, they are responsible for
managing. Examples of Epic applications include EpicCare Ambulatory for outpatient workflows, Stork for
obstetric workflows, and Cogito Ergo Sum, or Cogito, for analytics tools and content.



### Hyperdrive 

Technically, **Hyperspace** is a web‐based application. It runs on a web server, called
Hyperspace Web. When you launch the Hyperspace icon in training, you’re actually
launching a specialized web browser called **Hyperdrive**. The Hyperdrive client presents the
Hyperspace Web application to users, much like how a commercially available browser
﴾Chrome, Edge, Firefox, etc.﴿ presents your favorite web sites.


 
###  Chapter 2.2 - In-Class Scenario  

In the reporting world, users view reporting results and submit requests for additional reporting needs
while administrators create and distribute the reporting content. In this class, you’ll fulfill a report request
using Epic’s reporting tools.

The content of the scenario is considered "beyond the basics" and will not be tested on the exam.

### The Players 

### Payer 1 - Lorena, the Cogito Tools Administrator

Lorena works hard to deliver reporting content to users. She is a member of the Cogito reporting team at
Epic Health Systems.

### Payer 2 - Violet, the Clinic Manager

Violet oversees several clinics, including EMC Pain Medicine. She reviews patient safety metrics and meets
regularly with physicians and nurses to go over current safety standards and protocols in the clinic.

 
### The Scene 

Violet reviews the analytics needs for the new Opioid Patient Management program at Epic
Health Systems. The Opioid Stewardship Committee will review organization‐wide opioid
metrics monthly using the Epic‐released Opioid Management dashboard, which meets most
of the committee’s needs.

Violet has also outlined a new Pain Clinic Management dashboard that will help clinic
managers review patient diagnosis and provider prescribing trends in the clinic. They’ll use
this data to meet with providers in groups or individually to address concerns and best
practices while treating acute or chronic pain. 

### The Goals
 
1. Every patient who is prescribed a high MME opioid medication is co‐prescribed Naloxone.
2. Every patient who is prescribed >5 days’ supply of an opioid medication is co‐prescribed Naloxone.
3. Patients with chronic pain are referred to physical therapy to help them manage their pain long term.
4. Providers are consistently reviewing the PDMP when prescribing pain medication.


 
###  Clinical Terminology for Opioid Scenario 

**Opioids** are a class of drugs primarily used to **help relieve pain.**

Common prescription opioids include oxycodone .OxyContin., hydrocodone .Vicodin., morphine, and codeine. Most opioids are Schedule II
controlled substances, which are defined as drugs with a high potential for abuse, with use potentially
leading to severe psychological or physical dependence. Opioids have several side effects including
tolerance, physical dependence, and respiratory depression.
 
 
The opioid crisis was declared a national public health emergency on October 26, 2017. Fighting the
epidemic is a top priority for the White House, state and local governments, and healthcare organizations.
At Epic, we are working together with our customers to develop tools and workflows to address the crisis
by both providing the best patient care possible and meeting legislative requirements.

- **Opioid** – a type of drug or medication that reduces pain and releases dopamine by binding to
receptors in the brain.

- **Opioid Use Disorder .OUD.** –  or opioid addiction – a problematic pattern of opioid use leading to
impairment or distress.

- **Medications for Opioid Use Disorder MOUD** – the FDA has approved buprenorphine, methadone,
and naltrexone for medication treatment of OUD, which is associated with reduced overdose and
mortality.

- **Naloxone** – a rescue medication used for emergency treatment of opioid overdose
 
- **Prescription Drug Monitoring Program PDMP** – a statewide electronic database that records data
on controlled substance prescriptions.

- **Morphine Milligram Equivalents  MME** – a dosage’s equivalency to morphine; daily MME is used to
calculate risk of opioid overdose.




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

1. **Workbench Reports**: Customizable reports that allow users to filter, sort, and analyze data from Epic’s electronic health records.

2. **SlicerDicer**: A self-service data exploration tool that enables users to create ad-hoc reports and visualizations by slicing and dicing data sets.

3. **Clarity**: Epic’s relational database designed for detailed reporting, storing data extracted from the Chronicles database for large-scale analysis.

4. **Caboodle**: Epic’s enterprise data warehouse (EDW) that consolidates data from multiple sources, including Clarity, to provide a comprehensive view for analytics.

5. **Chronicles**: Epic’s primary non-relational database where real-time clinical and operational data is stored; used for day-to-day patient care activities.

6. **Data Model**: The structure that defines how data is stored and related within Epic, including entities like patients, encounters, and procedures.

7. **Metric-Based Components**: Dashboard elements that display performance metrics over time, helping users track and assess key performance indicators (KPIs).

8. **Cogito**: The umbrella term for Epic's analytics and reporting suite, which includes tools like Clarity, Caboodle, SlicerDicer, and Workbench Reports.

9. **Dashboards**: Visual displays in Epic that aggregate data from various sources, providing users with insights and quick access to key metrics and information.

10. **ETL (Extract, Transform, Load)**: The process used to extract data from Chronicles, transform it for analysis, and load it into Clarity and Caboodle for reporting purposes.

11. **Users**: The steps that a user takes in Epic are referred to as a workflow. For example, a clinician might open their schedule, review a patient’s medical history, open the patient’s chart,
place an order, and sign a note. Different users have different workflows. Nurses, physicians, registrars, coders, and report writers all log in to Epic for a variety of tasks. Everyone
who logs in to Epic is called a user. Users perform a variety of tasks using different parts of the Epic
system.

12. **User Workflows**: Users navigate to different activities in Hyperspace when completing their workflows. A scheduler can use the Appts activity to create a new appointment, a clinician can review messages from the In Basket activity, and a report writer can modify report settings from the Analytics Catalog activity.

13. **Administrators**: Administrators who build content to meet users’ needs.



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

The design aims to be user-friendly, though it can be complex due to the wide range of functions it covers. Each role within a healthcare facility, from doctors to receptionists, may have a different version of Hyperspace tailored to their needs.



## Hyperspace Tabs

The main tabs on Epic Hyperspace typically include:

1. **Patient Lists**: Displays lists of patients assigned to the user, allowing easy access to their medical records and information.
2. **Chart Review**: Provides a comprehensive view of a patient's medical history, including past visits, lab results, and notes.
3. **Visit Navigator**: Guides users through the documentation and order entry process during a patient visit.
4. **Order Entry**: Allows clinicians to place orders for medications, tests, and procedures.
5. **In Basket**: Functions as a messaging and task management tool, where users receive notifications, alerts, and messages.
6. **Schedule**: Displays and manages patient appointments, staff schedules, and room bookings.
7. **Care Everywhere**: Enables viewing and sharing of patient information across different healthcare systems using Epic. 

These tabs are often tailored to specific user roles, so not every user will see all of them.



## Hyperspace Tabs

The main tabs on Epic Hyperspace typically include:

1. **Patient Lists**: Displays lists of patients assigned to the user, allowing easy access to their medical records and information.
2. **Chart Review**: Provides a comprehensive view of a patient's medical history, including past visits, lab results, and notes.
3. **Visit Navigator**: Guides users through the documentation and order entry process during a patient visit.
4. **Order Entry**: Allows clinicians to place orders for medications, tests, and procedures.
5. **In Basket**: Functions as a messaging and task management tool, where users receive notifications, alerts, and messages.
6. **Schedule**: Displays and manages patient appointments, staff schedules, and room bookings.
7. **Care Everywhere**: Enables viewing and sharing of patient information across different healthcare systems using Epic. 

These tabs are often tailored to specific user roles, so not every user will see all of them.




### Clarity Administrator

Since the issue is with a Clarity-based report and the Chronicles data has been verified as valid, the problem likely lies within the Clarity reporting environment, such as data extraction, transformation, or loading (ETL) processes. A Clarity administrator is responsible for managing Clarity data extraction and ensuring the integrity of reports, making them the appropriate role to address this issue.


### Use ALT + = to refresh dashboard

when trying to add it to the dashboard, it's often because the dashboard needs to be refreshed for the new component to appear. Pressing `ALT + =` would refresh the dashboard and make the new component visible.


### The Metadata Editor

The Metadata Editor in Epic is used to manage and modify metadata associated with various reporting and analytics tools. This includes updating report tags, which help categorize and organize content within the Analytics Catalog, making it easier for users to find relevant reports. The other options are not typically managed through the Metadata Editor.



### SlicerDicer filters

In SlicerDicer, the granularity of a population is defined by the filters you apply, as they narrow down the dataset to specific criteria, such as age range, diagnosis, or time period. The filters determine which subset of the data is being analyzed, thus setting the level of detail or granularity of the population. While the data model is the underlying structure, it's the filters that dictate the specific population you're working with in SlicerDicer.

### SlicerDicer filtering and granularity 

The SlicerDicer session is based on the "Procedure Orders" data model, and the user has applied a filter for patients residing in Wisconsin. This means the session will display all procedure orders for those specific patients, regardless of who placed the orders. Therefore, option B best describes the defined population.


### SlicerDicer Measures 

In SlicerDicer, to change what is being displayed (such as switching from a count to an average), you need to modify the "Measures." Measures determine the type of data aggregation or calculation, such as count, average, sum, etc. By adjusting the measure, you can display the average age of all patients instead of just a count.


### SlicerDicer Measures 

In SlicerDicer, to change what is being displayed (such as switching from a count to an average), you need to modify the "Measures." Measures determine the type of data aggregation or calculation, such as count, average, sum, etc. By adjusting the measure, you can display the average age of all patients instead of just a count.


### Epic's Chronicles database, information is organized into "Master Files."

In Epic's Chronicles database, information is organized into "Master Files." 
Each Master File contains data related to a broad subject, such as patients, appointments, or medications. 
These Master Files are further subdivided into smaller data structures like records, contacts, and items.


### Epic's Chronicles database, information is organized into "Master Files."

In Epic's Chronicles database, information is organized into "Master Files." 
Each Master File contains data related to a broad subject, such as patients, appointments, or medications. 
These Master Files are further subdivided into smaller data structures like records, contacts, and items.


### Epic's Chronicles, a **related group** response

In Epic's Chronicles, a **related group**  response type allows for multiple related entries, where each line of data in one item corresponds to a line in another item.
This is typically used to represent complex data structures where elements need to be linked, such as different components of a medication order.


### Criteria tab of the Report Settings window

In the **Criteria tab** of the Report Settings window, users can define which data points (or fields) to use as criteria for filtering the report results.
This allows for precise control over which records are included based on specific conditions. 



### Criteria tab of the Report Settings window

In the **Criteria tab** of the Report Settings window, users can define which data points (or fields) to use as criteria for filtering the report results.
This allows for precise control over which records are included based on specific conditions. 


### Filters Data Model or Filters Data Set
 
Here is a breakdown of the acronyms and their descriptions:

1. **FDM (Filters Data Model)** - Real: Refers to data structures used to manage filters in SlicerDicer sessions. Creating a new SlicerDicer session might involve generating new filter records within this data model.
2. **FDS (Filters Data Set)** - Real: Represents a set of data linked to the filters in SlicerDicer. Adding a new component or configuring a session might create or modify records within FDS.
3. **HRX** - This acronym appears to be made-up or not specifically related to SlicerDicer in Epic.
4. **IDB (Integrated Data Base)** - While this could be a plausible acronym, it doesn’t directly align with Epic terminology for SlicerDicer data structures.
5. **IDM (Integrated Data Model)** - This also seems generic or unrelated to Epic-specific terms.

In summary, FDM and FDS are likely the appropriate choices for records created or modified when working with SlicerDicer sessions and components.

### Filter results based on the values in the display columns - Use action buttons to take action on the results

1. Filter results based on the values in the display columns**: Users can filter and sort data directly within the Results Viewer to analyze the results more effectively.
2. Use action buttons to take action on the results**: The Results Viewer allows users to interact with data through action buttons, such as to edit, follow up, or initiate further tasks based on the report results. 


###  In a Chronicles-based Workbench report, each row typically represents a record from a master file

These records contain all the relevant data points (items and values) associated with that specific entry in the master file.


###  **Summary Targets**  

A metric-based summary that tracks performance over time, showing different quarters and a cumulative quarter-to-date (QTD)
percentage. This kind of view is consistent with a "Summary Targets" setup,
which highlights progress toward specific benchmarks or goals across different time periods.




###  Dashboard Metrics

Epic provides benchmarking capabilities through tools that utilize Dashboard Metrics, which can be configured to show comparisons across other Epic community members. These metrics allow organizations to see how their performance stacks up against similar institutions.

Reporting Workbench is more focused on generating custom reports based on specific data points but does not inherently provide benchmarking across the Epic community.



###  public reporting

When viewing another user's Catalog in Epic, you can run public reports that are shared across the organization.
This allows you to see the same results that the user would see based on the same criteria and data access permissions.



### Security classes

In Epic, security classes are used to control what actions users can perform within the system, including the ability 
to edit public reports or export line-level details.
Security classes define the permissions and access rights for different functionalities, ensuring that only authorized users
can perform specific tasks. 



### Database Administrators 

Each of Epic's databases has an administrator. Database administrators sometimes oversee operation of more than one database. 


### The Chronicles Administrator

The Chronicles Administrator oversees the daily functioning and troubleshooting of Chronicles, as well as updates to the system. The Chronicles Administrator is most often referred to as the ODBA (Operational Database Administrator), or the Cache DBA. The ODBA is not part of the Cogito team, but they may assist in some troubleshooting related to Cogito functionality. Reasons to contact the Chronicles Administrator include: 

Workbench reports are displaying queuing errors 
Workbench reports are running slowly or not running 

### The Clarity Administrator

The Clarity Administrator oversees and troubleshoots nightly and ad-hoc Clarity ETL executions that move data from Chronicles to Clarity. Because of this, they are sometimes called the Clarity ETL Administrator. They might also be called the ETL Administrator (without mention of Clarity), particularly if they oversee both Clarity and Caboodle ETL. The Clarity Administrator is also responsible for managing Epic-released updates to Clarity and adding indexes to the Clarity database when appropriate. Reasons to contact the Clarity Administrator include: 

Requesting an ad hoc ETL into a test Clarity database to validate a report with test data 
A Clarity report looking at the last year's data isn't displaying anything for the most recent two months 
Corrupted or incorrect data has made its way into Clarity reports that used to work perfectly 

### The Caboodle Administrator

The Caboodle Administrator oversees and troubleshoots nightly and ad-hoc Caboodle ETL executions that move data from Clarity to Caboodle. Because of this, they are sometimes called the Caboodle ETL Administrator. They might also be called the ETL Administrator (without mention of Caboodle), particularly if they oversee both Clarity and Caboodle ETL. The Caboodle Administrator is also responsible for managing Epic-released updates to Caboodle and any custom Caboodle tables or columns an organization decides to create. Reasons to contact the Caboodle Administrator include: 

Requesting an ad hoc ETL into a test Caboodle database to validate a report with test data 
SlicerDicer sessions are missing data for a conspicuous date range 
Requesting to increase the file size limit for Data Gateway import files 
Cogito Project Manager 






### The Cogito Project Manager 

The Cogito Project Manager  is responsible for the success of the Cogito team.
have a detailed knowledge of the processes and policies that govern the reporting and analytics goals of the organization.

They have a high-level understanding of each of the databases. 

Reasons to contact the Cogito Project Manager include: 
1. Appropriately estimating time commitments for reporting projects 
2. Ensuring data governance on complex reporting projects 
3. Triaging or prioritizing reporting projects 
4. Business Intelligence Developer 

In Hyperspace, they work with SlicerDicer, Radar, and Reporting Workbench, but may also assist application analysts who 
are working with registries or extracts and need more understanding of the underlying Chronicles data. 

### Business Intelligence Developers

Business Intelligence Developers (BIDs) have some of the broadest responsibilities on the Cogito Team. 
They use all of Cogito's tools to retrieve and analyze data from all of Epic's databases. 
They get trained on Chronicles, Clarity, and Caboodle data structures and tools. 

### Application Analysts

Application Analysts may have different responsibilities depending on which application they specialize in. They interact most often with the Cogito team as subject matter experts (SMEs) who can help a report writer find the right data or understand a workflow used to populate the data for a report. Reasons to contact an Application Analysts may include: 

Needing someone to validate the data on a dashboard or report and make sure it is realistic and appropriate for that application 
Finding a specific data point populated by an end user workflow 

###  Caboodle Developer 

Caboodle Developers build the packages to bring data into Caboodle from Clarity and other non-Epic data sources. They know how and why all data comes into Caboodle. They may also be Caboodle BIDs, building SQL queries to retrieve data from Caboodle. Since Caboodle is the data source for SlicerDicer, these developers also are involved in building custom SlicerDicer Filter or even entire data models. Reasons to contact a Caboodle Developer may include: 

Need to add custom SlicerDicer Filter to an existing SlicerDicer Data Model 
Scoping out the possibility of building a SlicerDicer Data Model on non-Epic data 


###  Cogito Principal Trainer 

The Cogito Principal Trainer is responsible for customizing and delivering reporting training to users at each organization. This may be one person's full-time role, or a Principal Trainer may be responsible for several applications and include Cogito in their list of responsibilities. Reasons to contact a Cogito Principal Trainer may include: 

Planning for which users should receive specialized SlicerDicer training after go-live 
Some users have been incorrectly building Workbench reports and need re-training 
Generating and distributing tip sheets or other training tools for ongoing optimization projects 










Definitions for each term in the context of Epic Cogito fundamentals:

1. **Users**: Individuals who interact with Epic software, such as healthcare providers, administrators, and analysts.
2. **Workflow**: A series of tasks and processes in Epic that guide users through clinical or operational activities.
3. **Hyperspace**: The main user interface of Epic where users access various applications and perform tasks.
4. **Activity**: A specific function or screen within Epic Hyperspace where users can complete tasks, such as charting or scheduling.
5. **Epic menu**: The navigation menu in Hyperspace that provides access to various applications and activities.
6. **Epic search**: A tool within Hyperspace that allows users to quickly locate patients, activities, or records by entering keywords or identifiers.
7. **Chronicles**: Epic's NoSQL database that stores real-time data for all patient care and operational activities.
8. **Administrator**: A role responsible for managing system configurations, permissions, and overall functionality within Epic.
9. **Applications**: Software modules in Epic designed to handle specific aspects of healthcare delivery, such as billing, scheduling, or clinical documentation.
10. **Analyst**: A professional who configures, maintains, and optimizes Epic applications to support clinical and business workflows.
11. **Build**: The process of configuring and customizing Epic software to meet specific organizational needs.
12. **Record**: An entry in Chronicles or other Epic databases that stores information about patients, orders, or operational entities.
13. **Security**: The configuration of permissions and access controls that govern what users can see and do within Epic.
14. **Change management**: The process of controlling and implementing updates to Epic systems, ensuring minimal disruption to operations.
15. **Build tracker**: A tool used to monitor the progress of configuration changes and customizations being developed in Epic.
16. **Database Administrator**: A role that manages the performance, integrity, and security of Epic databases, including Clarity and Caboodle.
17. **Chronicles Administrator**: A specialist responsible for maintaining and troubleshooting the Chronicles database.
18. **Clarity Administrator**: A role focused on managing the Clarity database, which supports detailed reporting and data extraction.
19. **Caboodle Administrator**: A professional who oversees the Caboodle enterprise data warehouse, ensuring data is integrated and available for analytics.
20. **Cogito Project Manager**: A leader who coordinates analytics projects and resources, ensuring successful deployment of reporting and data tools.
21. **Business Intelligence Developer**: A developer who designs, builds, and maintains reports, dashboards, and data visualizations using Epic data sources.
22. **Application Analyst**: A role that involves configuring and optimizing specific Epic applications to ensure they meet clinical and operational needs.
23. **Caboodle Developer**: A specialist who creates and manages data structures, ETL processes, and reports within the Caboodle data warehouse.
24. **Cogito Tools Administrator**: A professional responsible for managing the setup, maintenance, and support of analytics tools within the Cogito suite.
25. **Cogito Principal Trainer**: An educator who trains staff on how to use Epic's analytics tools and ensures they can effectively leverage data for decision-making.



## What is EPIC Cogito 

EPIC Cogito is a business intelligence (BI) and analytics module within the EPIC electronic health record (EHR) system. It provides tools and features to analyze, report, and visualize healthcare data, making it easier for healthcare organizations to extract insights from the vast amounts of information stored in the EPIC system.

Here are some key features of EPIC Cogito:

1. **Reporting and Dashboards**: Cogito allows users to create reports and dashboards that present data in a clear, visual format. These can include metrics on patient care, hospital operations, financial performance, and more. Users can track trends, monitor key performance indicators (KPIs), and make data-driven decisions.

2. **Data Warehousing**: Cogito includes a data warehouse that consolidates data from various EPIC modules and external sources. This allows healthcare organizations to have a central repository of data for deeper analysis, reducing the need to access multiple systems.

3. **Self-Service Analytics**: Healthcare staff can access self-service tools to build their own reports and queries without needing extensive technical knowledge. This empowers clinicians, administrators, and other users to analyze data independently.

4. **Data Integration**: Cogito can integrate with other data sources, enabling organizations to combine EHR data with other relevant information, such as financial data, patient satisfaction surveys, and more, for a comprehensive view.

5. **Analytics Tools**: It provides predictive analytics, data mining, and other advanced analytic capabilities. This helps healthcare organizations identify patterns, predict patient outcomes, and improve efficiency.

EPIC Cogito is designed to support a range of users within healthcare organizations, from executives and managers looking at high-level trends to clinicians needing patient-specific information to improve care.


## What is EPIC Cogito

Epic Cogito is a suite of analytics and reporting tools integrated within the Epic electronic health record (EHR) system. Here are the key features and functionalities of Epic Cogito:

1. **Data Analytics**: Cogito provides healthcare organizations with robust data analytics capabilities, allowing them to analyze large volumes of clinical and operational data stored in the Epic EHR.

2. **Reporting Tools**: It includes tools for creating custom reports that can help healthcare providers and administrators track performance metrics, patient outcomes, and operational efficiency.

3. **Clinical Intelligence**: Cogito enables users to extract meaningful insights from clinical data, facilitating informed decision-making and improving patient care.

4. **Dashboards**: Users can create interactive dashboards that visualize key performance indicators (KPIs) and other important metrics, making it easier to monitor trends and identify areas for improvement.

5. **Integration with Epic**: Since Cogito is integrated within the Epic system, it provides seamless access to data and analytics, ensuring that users can easily generate reports and insights without needing to export data to other systems.

6. **Population Health Management**: The tool supports population health initiatives by allowing organizations to analyze patient data across different populations, helping to identify health trends and outcomes.

7. **User-Friendly Interface**: Cogito is designed to be user-friendly, enabling non-technical users to create reports and analyze data without needing extensive training in data analytics.

8. **Training and Support**: Epic provides training and support for users to help them effectively utilize the Cogito tools for their specific reporting and analytics needs.

In summary, Epic Cogito is a powerful analytics platform that enhances the ability of healthcare organizations to derive insights from their clinical and operational data, ultimately supporting better decision-making and improved patient outcomes.


## What is EPIC Coboodle

Epic Coboodle is a clinical decision support tool integrated within the Epic electronic health record (EHR) system. Here are some key points about Coboodle:

1. **Clinical Guidelines**: Coboodle provides healthcare professionals with access to evidence-based clinical guidelines and recommendations. It aims to assist clinicians in making informed decisions at the point of care.

2. **Integration with Epic EHR**: Coboodle is designed to work seamlessly within the Epic EHR platform, allowing healthcare providers to access clinical guidelines directly while documenting patient care or making treatment decisions.

3. **User-Friendly Interface**: The tool features a user-friendly interface that helps clinicians easily navigate through clinical guidelines, protocols, and care pathways.

4. **Customizable Content**: Organizations can customize Coboodle to reflect their own clinical practices and policies, ensuring that the content is relevant to their specific patient population and practice needs.

5. **Real-Time Updates**: Coboodle is regularly updated to reflect the latest clinical guidelines and research, ensuring that healthcare providers have access to the most current information.

6. **Improving Patient Care**: By providing quick access to guidelines and best practices, Coboodle aims to enhance patient care quality and safety, reduce variability in care, and support clinical decision-making.

Epic has two relational databases, Clarity and Caboodle, which approach these questions differently. Finding the appropriate tables and columns is beyond the scope of this self-study and is covered in CDW110 (Caboodle Data Model Fundamentals) and CLR110 (Clarity Data Model Fundamentals). 

Overall, Epic Coboodle serves as a valuable resource for clinicians, helping them to deliver evidence-based care efficiently within the Epic EHR environment.

