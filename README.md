# 7Shifts

7shifts is a cloud-based employee scheduling and labor management software designed specifically for the restaurant and hospitality industry. It's used to streamline the scheduling process, manage employee availability, track labor costs, and improve overall workforce management.

# Key features of 7shifts typically include:

  1.  Scheduling: The software allows managers to create and adjust employee schedules quickly and easily, taking into account factors like availability, labor laws, and business demands.

   2.  Communication: 7shifts often offers communication tools to help managers and employees stay connected. This can include messaging features and notifications about shift changes or updates.

  3.  Time and Attendance: The software might provide functionality for employees to clock in and out, and for managers to track attendance and monitor labor costs.

  4.  Labor Cost Management: Managers can often analyze labor costs in real-time, helping to optimize staffing levels and control expenses.

  5.  Integration: 7shifts may integrate with other restaurant management tools such as point-of-sale systems and payroll software.

  6.  Mobile App: Many workforce management systems, including 7shifts, offer mobile apps for both managers and employees. This allows for easier access to schedules, communication, and time tracking on the go.
    
  7.  Reporting: The software typically generates reports on various aspects of workforce management, providing insights into labor costs, employee performance, and scheduling efficiency.


# Introduction 

  - Company
The primary account of a customer. A company is a grouping of locations. It houses users, locations, and top-level settings that configure an account.
  - Location
The physical brick & mortar of a restaurant.
  - Department
These are sections of a restaurant.
Examples: Back of House, Front of House, Kitchen, Drive-through
  - Role
A role describes what job an employee is working that day.
Examples: Server, Prep Cook, etc.
  - User
Users (aka. Employee) is typically assigned to one or many locations, departments, and roles, and shows up for their scheduled shifts, and clocks in / out accordingly.
  - Shift
A user is scheduled to work a role at a location, likely in a department, at a specific time. This is their shift.
  - Time Punch
Time punches represent clock actions, including breaks, attestation, health checks, and various other jurisdictional compliance data.
A user clocks in and out of their scheduled shift.

# Dataset 
 For this project the dataset was generated synthetically. In this dataset there are 10000 rows with 10 columns. The columns are: shift_id,	employee_id,	employee_name,	shift_date,	start_time,	end_time,	duration,	request_status and 	swap_with	reason. 

# Data Overview
The dataset consists of various columns providing valuable insights into shift swapping:

shift_id: Unique identifier for shifts.
employee_id: Unique identifier for employees.
employee_name: Name of the employee.
shift_date: Date of the shift.
start_time: Start time of the shift.
end_time: End time of the shift.
duration: Duration of the shift.
request_status: Status of the swap request (rejected, approved, pending).
swap_with: Name of the employee the swap is requested with.
reason: Reason for the shift swap.

# Temporal Patterns
We analyze the distribution of shifts over time to identify trends and peak periods of shift swapping activity. This helps us understand if certain months experience higher demand for shift swaps:

<img width="500" alt="Screenshot 2023-08-25 at 9 59 01 AM" src="https://github.com/alirazi1992/7Shifts/assets/95105244/d334e16e-3db2-4edb-a9f2-d900a692450a">

# Request Status Analysis
We visualize the distribution of request statuses to understand the proportion of approved, rejected, and pending swap requests:


<img width="300" alt="Screenshot 2023-08-25 at 10 02 00 AM" src="https://github.com/alirazi1992/7Shifts/assets/95105244/42ca53d4-d4cc-45d2-b83d-7722fedc3602">

# Reasons for Swapping
We analyze the reasons behind shift swapping by creating a bar chart to visualize the distribution of the most common reasons for swaps:

<img width="500" alt="Screenshot 2023-08-25 at 10 03 38 AM" src="https://github.com/alirazi1992/7Shifts/assets/95105244/499bd88d-3c49-40e6-9727-89ab2fb6de50">





